# Function: <code>create_default_group</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581861200,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:664",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861200,
      "name": "create_default_group.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582011088,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:664",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582011088,
      "name": "create_default_group.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582199888,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:664",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199888,
      "name": "create_default_group.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582295104,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:664",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295104,
      "name": "create_default_group.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582460928,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:681",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460928,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582560256,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560256,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582867360,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867360,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940272,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:677",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940272,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970176,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:675",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970176,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305776,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:658",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305776,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583812528,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:658",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812528,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584433952,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:660",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584433952,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662688,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:660",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662688,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584895376,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:660",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584895376,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494203032,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494203032,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227636416,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227636416,
      "name": "create_default_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287896064,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287896064,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273663154,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273663154,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582528992,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528992,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582466160,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466160,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582519472,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582519472,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_default_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582600048,
      "name": "create_default_group",
      "external": false,
      "loc": "fs/configfs/dir.c:676",
      "file": "fs/configfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600048,
      "name": "create_default_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int create_default_group(struct config_group * parent_group, struct config_group * group, struct configfs_fragment * frag)
```
</details>
</li>
</ul>
