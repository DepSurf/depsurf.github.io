# Function: <code>umount_list</code>

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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491188,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:488",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581633140,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:488",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581791855,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:488",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581878751,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:489",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582003661,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582081613,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
void umount_list(struct list_head * to_umount, struct list_head * to_restore)
```

```json
{
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582315024,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:481",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pnode.c:propagate_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582315024,
      "name": "umount_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void umount_list(struct list_head * to_umount, struct list_head * to_restore)
```

```json
{
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582367936,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:481",
      "file": "fs/pnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pnode.c:propagate_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367936,
      "name": "umount_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582397445,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:481",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582718981,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:481",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583263717,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:481",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583845445,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:481",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584063682,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:519",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584278810,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:519",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493616092,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227158480,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287202452,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273260082,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582050349,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581987901,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582041629,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
  "name": "umount_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582113357,
      "name": "umount_list",
      "external": false,
      "loc": "fs/pnode.c:482",
      "file": "fs/pnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pnode.c:propagate_umount"
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
void umount_list(struct list_head * to_umount, struct list_head * to_restore)
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
void umount_list(struct list_head * to_umount, struct list_head * to_restore)
```
</details>
</li>
</ul>
