# Function: <code>kobject_get_unless_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582957443,
      "name": "kobject_get_unless_zero",
      "external": false,
      "loc": "lib/kobject.c:604",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583243107,
      "name": "kobject_get_unless_zero",
      "external": false,
      "loc": "lib/kobject.c:604",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
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
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583358419,
      "name": "kobject_get_unless_zero",
      "external": false,
      "loc": "lib/kobject.c:604",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208723,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:604",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "block/genhd.c:get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209424,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588758123,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:604",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "block/genhd.c:get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758944,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589137267,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:619",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136192,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589371411,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:619",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371040,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589828229,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827904,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590054373,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590054048,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049280,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:668",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "block/genhd.c:exact_lock",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049280,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199072,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:665",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/block_dev.c:blkdev_get_no_open",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199072,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585082144,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:665",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "fs/block_dev.c:blkdev_get_no_open",
        "block/genhd.c:disk_uevent",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082144,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585529088,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:665",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "block/bdev.c:blkdev_get_no_open",
        "block/genhd.c:disk_uevent",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529088,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682944,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:633",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "block/bdev.c:blkdev_get_no_open",
        "block/genhd.c:disk_uevent",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682944,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595763680,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:641",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "block/bdev.c:blkdev_get_no_open",
        "block/genhd.c:disk_uevent",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595763680,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596288080,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:642",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "block/bdev.c:blkdev_get_no_open",
        "block/genhd.c:blk_mark_disk_dead",
        "block/genhd.c:disk_uevent",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596288080,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597172944,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:649",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:exact_lock",
        "fs/char_dev.c:chrdev_open",
        "fs/char_dev.c:chrdev_open",
        "block/bdev.c:blkdev_get_no_open",
        "block/genhd.c:blk_report_disk_dead",
        "block/genhd.c:disk_uevent",
        "lib/kobject.c:kset_find_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597172944,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503831060,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503830128,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236451188,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236450264,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297678932,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297676368,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279723856,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279722634,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589656629,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656304,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589382453,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382128,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590100005,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590099680,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```

```json
{
  "name": "kobject_get_unless_zero",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590150243,
      "name": "kobject_get_unless_zero",
      "external": true,
      "loc": "lib/kobject.c:650",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_find_obj"
      ],
      "caller_func": [
        "fs/char_dev.c:cdev_get",
        "block/genhd.c:get_disk_and_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590151008,
      "name": "kobject_get_unless_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct kobject * kobject_get_unless_zero(struct kobject * kobj)
```
</details>
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
