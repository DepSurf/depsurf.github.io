# Function: <code>fill_item_path</code>

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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581864384,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:57",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582014233,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:57",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582202642,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:57",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582297770,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:57",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582464036,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582563067,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
void fill_item_path(struct config_item * item, char * buffer, int length)
```

```json
{
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870736,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
      "addr": 18446744071582870736,
      "name": "fill_item_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void fill_item_path(struct config_item * item, char * buffer, int length)
```

```json
{
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943600,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
      "addr": 18446744071582943600,
      "name": "fill_item_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582971288,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:41",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583306888,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:41",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583813731,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:41",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void fill_item_path(struct config_item * item, char * buffer, int length)
```

```json
{
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435120,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:41",
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
      "addr": 18446744071584435120,
      "name": "fill_item_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void fill_item_path(struct config_item * item, char * buffer, int length)
```

```json
{
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663856,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:41",
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
      "addr": 18446744071584663856,
      "name": "fill_item_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void fill_item_path(struct config_item * item, char * buffer, int length)
```

```json
{
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896576,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:41",
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
      "addr": 18446744071584896576,
      "name": "fill_item_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494207340,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227639704,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287901404,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273667122,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582531803,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582468971,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582522283,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
  "name": "fill_item_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582602973,
      "name": "fill_item_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:43",
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
void fill_item_path(struct config_item * item, char * buffer, int length)
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
void fill_item_path(struct config_item * item, char * buffer, int length)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void fill_item_path(struct config_item * item, char * buffer, int length)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
