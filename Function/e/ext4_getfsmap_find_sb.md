# Function: <code>ext4_getfsmap_find_sb</code>

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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581936188,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:324",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582085061,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:324",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582272853,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582371493,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582539834,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582640778,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
unsigned int ext4_getfsmap_find_sb(struct super_block * sb, ext4_group_t agno, struct list_head * meta_list)
```

```json
{
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951264,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951264,
      "name": "ext4_getfsmap_find_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
unsigned int ext4_getfsmap_find_sb(struct super_block * sb, ext4_group_t agno, struct list_head * meta_list)
```

```json
{
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025680,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025680,
      "name": "ext4_getfsmap_find_sb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583049837,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583387453,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583901565,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584527133,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584756188,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584988924,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:314",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494292968,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227725892,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288007676,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273735594,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582609514,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582546682,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582599626,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
  "name": "ext4_getfsmap_find_sb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582681786,
      "name": "ext4_getfsmap_find_sb",
      "external": false,
      "loc": "fs/ext4/fsmap.c:311",
      "file": "fs/ext4/fsmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int ext4_getfsmap_find_sb(struct super_block * sb, ext4_group_t agno, struct list_head * meta_list)
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
unsigned int ext4_getfsmap_find_sb(struct super_block * sb, ext4_group_t agno, struct list_head * meta_list)
```
</details>
</li>
</ul>
