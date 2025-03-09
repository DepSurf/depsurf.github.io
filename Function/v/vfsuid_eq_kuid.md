# Function: <code>vfsuid_eq_kuid</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid)
```

```json
{
  "name": "vfsuid_eq_kuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583627767,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_open",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704321,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_owner_or_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717263,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894930,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584182466,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584191739,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585137886,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586160640,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160640,
      "name": "vfsuid_eq_kuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid)
```

```json
{
  "name": "vfsuid_eq_kuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583834537,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_open",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583920250,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_owner_or_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583934685,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584118976,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584366160,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:generic_setlease"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584409933,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419240,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585367115,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586398512,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398512,
      "name": "vfsuid_eq_kuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid)
```

```json
{
  "name": "vfsuid_eq_kuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584040553,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_open",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:__check_sticky",
        "fs/namei.c:pick_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125946,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_owner_or_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140925,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:setattr_prepare",
        "fs/attr.c:setattr_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333800,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584584495,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:generic_setlease"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584630685,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:posix_acl_permission",
        "fs/posix_acl.c:posix_acl_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584640057,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585601851,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663456,
      "name": "vfsuid_eq_kuid",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:79",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586663456,
      "name": "vfsuid_eq_kuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
