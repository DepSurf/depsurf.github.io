# Function: <code>ext4_fc_replay_del_range</code>

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
int ext4_fc_replay_del_range(struct super_block * sb, struct ext4_fc_tl * tl)
```

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385200,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1770",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385200,
      "name": "ext4_fc_replay_del_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583407712,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1769",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407712,
      "name": "ext4_fc_replay_del_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1750",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753872,
      "name": "ext4_fc_replay_del_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071592272538,
      "name": "ext4_fc_replay_del_range.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1830",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314560,
      "name": "ext4_fc_replay_del_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071594054337,
      "name": "ext4_fc_replay_del_range.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1839",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962176,
      "name": "ext4_fc_replay_del_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071596085645,
      "name": "ext4_fc_replay_del_range.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1839",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190464,
      "name": "ext4_fc_replay_del_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596609139,
      "name": "ext4_fc_replay_del_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fc_replay_del_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_fc_replay_del_range",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:1839",
      "file": "fs/ext4/fast_commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_replay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585423360,
      "name": "ext4_fc_replay_del_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071597514794,
      "name": "ext4_fc_replay_del_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int ext4_fc_replay_del_range(struct super_block * sb, struct ext4_fc_tl * tl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ext4_fc_replay_del_range(struct super_block * sb, struct ext4_fc_tl * tl)
```
</details>
</li>
</ul>
