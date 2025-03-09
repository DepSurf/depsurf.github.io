# Function: <code>ext4_ext_replay_set_iblocks</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006128,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5919",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006128,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1099
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
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031872,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5925",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031872,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5959",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253842,
      "name": "ext4_ext_replay_set_iblocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583368512,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1146
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
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5972",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594034850,
      "name": "ext4_ext_replay_set_iblocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583880464,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1186
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
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5982",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596068076,
      "name": "ext4_ext_replay_set_iblocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584504944,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1182
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
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5953",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596591732,
      "name": "ext4_ext_replay_set_iblocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584733440,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1182
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
int ext4_ext_replay_set_iblocks(struct inode * inode)
```

```json
{
  "name": "ext4_ext_replay_set_iblocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_replay_set_iblocks",
      "external": true,
      "loc": "fs/ext4/extents.c:5988",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597497520,
      "name": "ext4_ext_replay_set_iblocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584965968,
      "name": "ext4_ext_replay_set_iblocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1182
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_ext_replay_set_iblocks(struct inode * inode)
```
</details>
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
