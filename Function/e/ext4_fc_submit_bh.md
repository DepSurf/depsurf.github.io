# Function: <code>ext4_fc_submit_bh</code>

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
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384144,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:612",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384144,
      "name": "ext4_fc_submit_bh",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406976,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:612",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406976,
      "name": "ext4_fc_submit_bh",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751280,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:580",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751280,
      "name": "ext4_fc_submit_bh",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584308064,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:659",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_perform_commit",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308064,
      "name": "ext4_fc_submit_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956432,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:660",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956432,
      "name": "ext4_fc_submit_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585184752,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:660",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184752,
      "name": "ext4_fc_submit_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
```

```json
{
  "name": "ext4_fc_submit_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417648,
      "name": "ext4_fc_submit_bh",
      "external": false,
      "loc": "fs/ext4/fast_commit.c:660",
      "file": "fs/ext4/fast_commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fast_commit.c:ext4_fc_write_tail",
        "fs/ext4/fast_commit.c:ext4_fc_reserve_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417648,
      "name": "ext4_fc_submit_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void ext4_fc_submit_bh(struct super_block * sb, bool is_tail)
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
