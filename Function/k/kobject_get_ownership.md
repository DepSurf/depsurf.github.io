# Function: <code>kobject_get_ownership</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589135593,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589138144,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589370441,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372992,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589827529,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589830048,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590053673,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590056192,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585049369,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585052224,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585199161,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202016,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585082233,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085088,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585529177,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532016,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586683193,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586685824,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(const struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595763961,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595766912,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(const struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596288361,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:50",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596291312,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_get_ownership(const struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597173225,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:50",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597176176,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503829640,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503833752,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236449584,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236452280,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297676628,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297681312,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279722746,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279725374,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589655929,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658448,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589381753,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589384272,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590099305,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590101824,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
```

```json
{
  "name": "kobject_get_ownership",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590149609,
      "name": "kobject_get_ownership",
      "external": true,
      "loc": "lib/kobject.c:48",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_get_ownership"
      ],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_create_bin_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_create_file_ns",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590152128,
      "name": "kobject_get_ownership",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void kobject_get_ownership(struct kobject * kobj, kuid_t * uid, kgid_t * gid)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject * kobj</code> ➡️ <code>const struct kobject * kobj</code>
</li>
</ul>
</details>
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
