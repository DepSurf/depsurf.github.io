# Function: <code>ext4_dx_csum_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581609643,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:466",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:do_split"
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581801965,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:465",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581891405,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:465",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582086227,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:465",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582235843,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:466",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421760,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:467",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421760,
      "name": "ext4_dx_csum_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521248,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:468",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521248,
      "name": "ext4_dx_csum_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582694100,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582796292,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583104944,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:490",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583104944,
      "name": "ext4_dx_csum_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184000,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:486",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184000,
      "name": "ext4_dx_csum_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583217472,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:488",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:make_indexed_dir"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583571947,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:489",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:make_indexed_dir"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584097928,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:512",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:make_indexed_dir"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584731512,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:517",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584954824,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:517",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585178400,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:519",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_handle_dirty_dx_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494466464,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227902728,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288223168,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273872556,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582765028,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582702196,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582755268,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_csum_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582840164,
      "name": "ext4_dx_csum_set",
      "external": false,
      "loc": "fs/ext4/namei.c:483",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename_dir_finish",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void ext4_dx_csum_set(struct inode * inode, struct ext4_dir_entry * dirent)
```
</details>
</li>
</ul>
