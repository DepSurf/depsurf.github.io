# Function: <code>internal_change_owner</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542320,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542320,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582849561,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:563",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582922617,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:564",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582950297,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:575",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583285529,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:575",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583790563,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:585",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584410163,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:585",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584638723,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:585",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584871011,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:598",
      "file": "fs/sysfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494179784,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494179784,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227616888,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227616888,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287866432,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287866432,
      "name": "internal_change_owner",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273644972,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273644972,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511056,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511056,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448224,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448224,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582501536,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501536,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "internal_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582144,
      "name": "internal_change_owner",
      "external": false,
      "loc": "fs/sysfs/file.c:562",
      "file": "fs/sysfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_change_owner",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582144,
      "name": "internal_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int internal_change_owner(struct kernfs_node * kn, kuid_t kuid, kgid_t kgid)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
