# Function: <code>ioctl_file_dedupe_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581235589,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:571",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313477,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:575",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581365182,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:577",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581506647,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:578",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581663465,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:578",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749815,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:587",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581867130,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:587",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581939530,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
int ioctl_file_dedupe_range(struct file * file, struct file_dedupe_range * argp)
```

```json
{
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167696,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:620",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167696,
      "name": "ioctl_file_dedupe_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int ioctl_file_dedupe_range(struct file * file, struct file_dedupe_range * argp)
```

```json
{
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214224,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:620",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214224,
      "name": "ioctl_file_dedupe_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582242718,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:623",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582560542,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:420",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583089676,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:416",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583657539,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:416",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583874907,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:416",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584081936,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:417",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493426540,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227008148,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286984888,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273128410,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581908266,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581845850,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581899578,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
  "name": "ioctl_file_dedupe_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581969210,
      "name": "ioctl_file_dedupe_range",
      "external": false,
      "loc": "fs/ioctl.c:588",
      "file": "fs/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:do_vfs_ioctl"
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
int ioctl_file_dedupe_range(struct file * file, struct file_dedupe_range * argp)
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
int ioctl_file_dedupe_range(struct file * file, struct file_dedupe_range * argp)
```
</details>
</li>
</ul>
