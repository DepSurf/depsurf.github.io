# Function: <code>sget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581006224,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:528",
      "file": "fs/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/super.c:mount_ns",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/super.c:mount_single"
      ],
      "caller_func": [
        "fs/libfs.c:mount_pseudo",
        "fs/kernfs/mount.c:kernfs_mount_ns",
        "fs/devpts/inode.c:devpts_mount",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006224,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164608,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:536",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/libfs.c:mount_pseudo",
        "fs/devpts/inode.c:devpts_mount",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164608,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241568,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:535",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241568,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288912,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:538",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288912,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428576,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:538",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428576,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586784,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:548",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586784,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672688,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:552",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672688,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789696,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:570",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789696,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861936,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861936,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582087872,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087872,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133536,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133536,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582158304,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:577",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582158304,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475280,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:577",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475280,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 686
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997376,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997376,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583559200,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:619",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559200,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583775456,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:626",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775456,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982080,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:803",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982080,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493331568,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493331568,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226928628,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226928628,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286876016,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286876016,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273065162,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273065162,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830672,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830672,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768336,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768336,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821984,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821984,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct super_block * sget(struct file_system_type * type, int (*)(struct super_block *, void *) test, int (*)(struct super_block *, void *) set, int flags, void * data)
```

```json
{
  "name": "sget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892240,
      "name": "sget",
      "external": true,
      "loc": "fs/super.c:576",
      "file": "fs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_single",
        "fs/super.c:mount_nodev",
        "fs/super.c:mount_bdev",
        "fs/ecryptfs/main.c:ecryptfs_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892240,
      "name": "sget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
