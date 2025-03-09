# Function: <code>swap_inode_boot_loader</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581600177,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:93",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581791965,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:94",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581881609,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:92",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582026913,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:94",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582178096,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:96",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582368504,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:97",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582467813,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634400,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634400,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735376,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735376,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583045104,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045104,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121376,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121376,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
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
long int swap_inode_boot_loader(struct super_block * sb, struct user_namespace * mnt_userns, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583146576,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:115",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583146576,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1335
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
long int swap_inode_boot_loader(struct super_block * sb, struct user_namespace * mnt_userns, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487040,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:115",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487040,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
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
long int swap_inode_boot_loader(struct super_block * sb, struct user_namespace * mnt_userns, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584013552,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:356",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013552,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
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
long int swap_inode_boot_loader(struct super_block * sb, struct user_namespace * mnt_userns, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644016,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:365",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644016,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1348
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
long int swap_inode_boot_loader(struct super_block * sb, struct mnt_idmap * idmap, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584867376,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:362",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867376,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
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
long int swap_inode_boot_loader(struct super_block * sb, struct mnt_idmap * idmap, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585100272,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:371",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:__ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100272,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494392808,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494392808,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227830344,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227830344,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288133984,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288133984,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273816032,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273816032,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704112,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704112,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641280,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641280,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693968,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693968,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```

```json
{
  "name": "swap_inode_boot_loader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582778352,
      "name": "swap_inode_boot_loader",
      "external": false,
      "loc": "fs/ext4/ioctl.c:113",
      "file": "fs/ext4/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778352,
      "name": "swap_inode_boot_loader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int swap_inode_boot_loader(struct super_block * sb, struct inode * inode)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, inode</code> ➡️ <code>sb, mnt_userns, inode</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * mnt_userns</code>
</li>
</ul>
</details>
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
