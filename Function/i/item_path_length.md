# Function: <code>item_path_length</code>

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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581864220,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:46",
      "file": "fs/configfs/symlink.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582014131,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:46",
      "file": "fs/configfs/symlink.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:46",
      "file": "fs/configfs/symlink.c",
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:46",
      "file": "fs/configfs/symlink.c",
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
int item_path_length(struct config_item * item)
```

```json
{
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870656,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_get_target_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870656,
      "name": "item_path_length",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int item_path_length(struct config_item * item)
```

```json
{
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943520,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_get_target_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943520,
      "name": "item_path_length",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582971180,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:30",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_get_target_path"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583306780,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:30",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_get_target_path"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583813629,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:30",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_get_target_path"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584435358,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:30",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_get_target_path"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584664094,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:30",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_get_target_path"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584896814,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:30",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_get_target_path"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227639568,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273666970,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_symlink"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
  "name": "item_path_length",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "item_path_length",
      "external": false,
      "loc": "fs/configfs/symlink.c:32",
      "file": "fs/configfs/symlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:create_link"
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
int item_path_length(struct config_item * item)
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
int item_path_length(struct config_item * item)
```
</details>
</li>
</ul>
