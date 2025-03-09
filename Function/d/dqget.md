# Function: <code>dqget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407632,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:832",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407632,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1165
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589840,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:839",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589840,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678256,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:836",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678256,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731920,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:837",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731920,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1150
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878720,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:844",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878720,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1123
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064880,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:841",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064880,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157936,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:841",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157936,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320608,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:847",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320608,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419808,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419808,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715520,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:846",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715520,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786688,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:847",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786688,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 934
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582814160,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:845",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814160,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1071
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:850",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592246629,
      "name": "dqget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071583143968,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:860",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594027343,
      "name": "dqget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583629952,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1117
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:860",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596062819,
      "name": "dqget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071584235008,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:918",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596586852,
      "name": "dqget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071584465440,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:924",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl_setproject",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597492622,
      "name": "dqget.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071584688608,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1119
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494022536,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494022536,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227487292,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227487292,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287675584,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287675584,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1864
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273534946,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273534946,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1362
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388544,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388544,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326240,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326240,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379024,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379024,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
struct dquot * dqget(struct super_block * sb, struct kqid qid)
```

```json
{
  "name": "dqget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455360,
      "name": "dqget",
      "external": true,
      "loc": "fs/quota/dquot.c:848",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_get_dqblk",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:dquot_transfer",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455360,
      "name": "dqget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1067
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
