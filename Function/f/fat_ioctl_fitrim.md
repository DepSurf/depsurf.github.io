# Function: <code>fat_ioctl_fitrim</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582801447,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:124",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582977532,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583083740,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
int fat_ioctl_fitrim(struct inode * inode, long unsigned int arg)
```

```json
{
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398640,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398640,
      "name": "fat_ioctl_fitrim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int fat_ioctl_fitrim(struct inode * inode, long unsigned int arg)
```

```json
{
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514176,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514176,
      "name": "fat_ioctl_fitrim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583540957,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583898957,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584475758,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585139822,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:126",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585368929,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:126",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585603665,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:126",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494789420,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228209400,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288624652,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274119284,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583052476,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582989628,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583041084,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
  "name": "fat_ioctl_fitrim",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583130220,
      "name": "fat_ioctl_fitrim",
      "external": false,
      "loc": "fs/fat/file.c:125",
      "file": "fs/fat/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_generic_ioctl"
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
int fat_ioctl_fitrim(struct inode * inode, long unsigned int arg)
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
int fat_ioctl_fitrim(struct inode * inode, long unsigned int arg)
```
</details>
</li>
</ul>
