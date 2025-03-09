# Function: <code>configfs_get_target_path</code>

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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581864161,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:234",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582014072,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:234",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582202488,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:234",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582297616,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:234",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582463888,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:220",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870848,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870848,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943712,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943712,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971104,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:56",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971104,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306704,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:56",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306704,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813552,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:56",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813552,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435280,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:56",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435280,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664016,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:56",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664016,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
```

```json
{
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896736,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:56",
      "file": "fs/configfs/symlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896736,
      "name": "configfs_get_target_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494207184,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227639508,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287901156,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273666934,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
  "name": "configfs_get_target_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582602817,
      "name": "configfs_get_target_path",
      "external": false,
      "loc": "fs/configfs/symlink.c:58",
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
int configfs_get_target_path(struct config_item * item, struct config_item * target, char * path)
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
