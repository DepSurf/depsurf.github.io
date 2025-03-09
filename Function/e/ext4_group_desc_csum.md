# Function: <code>ext4_group_desc_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653504,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2054",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653504,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885536,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2173",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885536,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974544,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2198",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974544,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582190816,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2256",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190816,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339488,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2259",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339488,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528976,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2300",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528976,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629872,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2362",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629872,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802528,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2405",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802528,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905888,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905888,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219552,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2577",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219552,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320976,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2782",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320976,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342096,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2808",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342096,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681232,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2794",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681232,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236800,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:3173",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236800,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584878768,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:3162",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878768,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585105968,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:3218",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585105968,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585338304,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:3224",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338304,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494558424,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494558424,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228019536,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228019536,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288378448,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288378448,
      "name": "ext4_group_desc_csum",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273960714,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273960714,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874624,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874624,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811776,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811776,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582863504,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863504,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
__le16 ext4_group_desc_csum(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950176,
      "name": "ext4_group_desc_csum",
      "external": false,
      "loc": "fs/ext4/super.c:2423",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_group_desc_csum_set",
        "fs/ext4/super.c:ext4_group_desc_csum_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950176,
      "name": "ext4_group_desc_csum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
