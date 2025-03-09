# Function: <code>find_inode_by_ino_rcu</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205616,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1515",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205616,
      "name": "find_inode_by_ino_rcu",
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253056,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1514",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253056,
      "name": "find_inode_by_ino_rcu",
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582278928,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1521",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278928,
      "name": "find_inode_by_ino_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1525",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229896,
      "name": "find_inode_by_ino_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582601776,
      "name": "find_inode_by_ino_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1606",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594009791,
      "name": "find_inode_by_ino_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583138336,
      "name": "find_inode_by_ino_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1608",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596050990,
      "name": "find_inode_by_ino_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583709904,
      "name": "find_inode_by_ino_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1652",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596573548,
      "name": "find_inode_by_ino_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583927376,
      "name": "find_inode_by_ino_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "find_inode_by_ino_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_inode_by_ino_rcu",
      "external": true,
      "loc": "fs/inode.c:1600",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_update_other_inode_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597478057,
      "name": "find_inode_by_ino_rcu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584133968,
      "name": "find_inode_by_ino_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct inode * find_inode_by_ino_rcu(struct super_block * sb, long unsigned int ino)
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
