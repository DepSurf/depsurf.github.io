# Function: <code>timespec64_trunc</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699040,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2115",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/configfs/inode.c:configfs_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699040,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785392,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2122",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785392,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903712,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2154",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:current_time",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/attr.c:setattr_copy",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/configfs/inode.c:configfs_setattr",
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903712,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976048,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976048,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493481952,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493481952,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227043544,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227043544,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287043296,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287043296,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273159600,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273159600,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944784,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944784,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882352,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882352,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936096,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936096,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```

```json
{
  "name": "timespec64_trunc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007536,
      "name": "timespec64_trunc",
      "external": true,
      "loc": "fs/inode.c:2165",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_truncate_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007536,
      "name": "timespec64_trunc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran)
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
