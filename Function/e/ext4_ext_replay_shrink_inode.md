# Function: <code>ext4_ext_replay_shrink_inode</code>

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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005696,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5872",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay_del_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005696,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031440,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5878",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031440,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368080,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5909",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368080,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880000,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5922",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880000,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584504464,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5934",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504464,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584732960,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5905",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584732960,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_replay_shrink_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965488,
      "name": "ext4_ext_replay_shrink_inode",
      "external": true,
      "loc": "fs/ext4/extents.c:5940",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965488,
      "name": "ext4_ext_replay_shrink_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
void ext4_ext_replay_shrink_inode(struct inode * inode, ext4_lblk_t end)
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
