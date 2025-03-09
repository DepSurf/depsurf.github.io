# Function: <code>lookup_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * lookup_mnt(struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129152,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:679",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129152,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vfsmount * lookup_mnt(struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295024,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:679",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295024,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373856,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:656",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373856,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581429040,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:657",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581429040,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570928,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:717",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570928,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726240,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:727",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726240,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812784,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:639",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812784,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932864,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932864,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005504,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005504,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582242512,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242512,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291504,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291504,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318608,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:650",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318608,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639056,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:652",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639056,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176048,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:695",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176048,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750816,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:806",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750816,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583967360,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:715",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967360,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179824,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:722",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_down_one",
        "fs/namei.c:__traverse_mounts",
        "fs/namespace.c:do_lock_mount",
        "fs/namespace.c:do_lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179824,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493526808,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493526808,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227080168,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227080168,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287093376,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287093376,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273193810,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273193810,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974240,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974240,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911808,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911808,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965520,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965520,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
struct vfsmount * lookup_mnt(const struct path * path)
```

```json
{
  "name": "lookup_mnt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035984,
      "name": "lookup_mnt",
      "external": true,
      "loc": "fs/namespace.c:636",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:follow_mount",
        "fs/namei.c:follow_down",
        "fs/namei.c:follow_down_one",
        "fs/namei.c:follow_managed",
        "fs/namespace.c:lock_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035984,
      "name": "lookup_mnt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
