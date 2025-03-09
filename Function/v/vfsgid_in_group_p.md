# Function: <code>vfsgid_in_group_p</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfsgid_in_group_p",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583610792,
      "name": "vfsgid_in_group_p",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:126",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583705150,
      "name": "vfsgid_in_group_p",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:126",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:mode_strip_sgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717829,
      "name": "vfsgid_in_group_p",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:126",
      "file": "fs/attr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/attr.c:setattr_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584177737,
      "name": "vfsgid_in_group_p",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:126",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138111,
      "name": "vfsgid_in_group_p",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:126",
      "file": "fs/fat/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/file.c:fat_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585327354,
      "name": "vfsgid_in_group_p",
      "external": false,
      "loc": "include/linux/mnt_idmapping.h:126",
      "file": "fs/fuse/acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/acl.c:fuse_set_acl"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int vfsgid_in_group_p(vfsgid_t vfsgid)
```

```json
{
  "name": "vfsgid_in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115536,
      "name": "vfsgid_in_group_p",
      "external": true,
      "loc": "fs/mnt_idmapping.c:219",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:mode_strip_sgid",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115536,
      "name": "vfsgid_in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int vfsgid_in_group_p(vfsgid_t vfsgid)
```

```json
{
  "name": "vfsgid_in_group_p",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331792,
      "name": "vfsgid_in_group_p",
      "external": true,
      "loc": "fs/mnt_idmapping.c:189",
      "file": "fs/mnt_idmapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/inode.c:mode_strip_sgid",
        "fs/attr.c:setattr_prepare",
        "fs/posix_acl.c:posix_acl_update_mode",
        "fs/posix_acl.c:posix_acl_permission",
        "fs/fat/file.c:fat_setattr",
        "fs/fuse/acl.c:fuse_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331792,
      "name": "vfsgid_in_group_p",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int vfsgid_in_group_p(vfsgid_t vfsgid)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
