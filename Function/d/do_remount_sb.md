# Function: <code>do_remount_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_remount_sb(struct super_block * sb, int flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008496,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:747",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:do_emergency_remount",
        "fs/super.c:mount_single",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008496,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_remount_sb(struct super_block * sb, int flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166912,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:761",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166912,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_remount_sb(struct super_block * sb, int flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243888,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:807",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243888,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_remount_sb(struct super_block * sb, int flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291296,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:810",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291296,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_remount_sb(struct super_block * sb, int sb_flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430960,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:810",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430960,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_remount_sb(struct super_block * sb, int sb_flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589104,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:842",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589104,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
int do_remount_sb(struct super_block * sb, int sb_flags, void * data, int force)
```

```json
{
  "name": "do_remount_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675056,
      "name": "do_remount_sb",
      "external": true,
      "loc": "fs/super.c:846",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:do_emergency_remount_callback",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:ksys_umount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675056,
      "name": "do_remount_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sb_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int do_remount_sb(struct super_block * sb, int sb_flags, void * data, int force)
```
</details>
</li>
</ul>
