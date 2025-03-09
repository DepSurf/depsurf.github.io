# Function: <code>ext4_sample_last_mounted</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582268599,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:384",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582367223,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:384",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582535365,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582636361,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943760,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:769",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943760,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018928,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:774",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018928,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583044736,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:790",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044736,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583382016,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:791",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583382016,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895200,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:790",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895200,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520416,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:811",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520416,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749264,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:833",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749264,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
```

```json
{
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982144,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:807",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982144,
      "name": "ext4_sample_last_mounted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494288548,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227720728,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288002104,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273732204,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605097,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582542265,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582595209,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "ext4_sample_last_mounted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582677273,
      "name": "ext4_sample_last_mounted",
      "external": false,
      "loc": "fs/ext4/file.c:397",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_sample_last_mounted(struct super_block * sb, struct vfsmount * mnt)
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
