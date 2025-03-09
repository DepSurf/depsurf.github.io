# Function: <code>superblock_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582265546,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1914",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_sb_kern_mount"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582482422,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1987",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582575318,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1995",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int superblock_has_perm(const struct cred * cred, struct super_block * sb, u32 perms, struct common_audit_data * ad)
```

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582664128,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1976",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582664128,
      "name": "superblock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int superblock_has_perm(const struct cred * cred, struct super_block * sb, u32 perms, struct common_audit_data * ad)
```

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582820064,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1990",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582820064,
      "name": "superblock_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583013516,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:2103",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583128172,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1917",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583315100,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1961",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583448211,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583797403,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1916",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583920043,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1925",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583948619,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1985",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584302499,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1977",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584917264,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1915",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585626608,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1914",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585856719,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1914",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586106431,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1954",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495209624,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228581828,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289143932,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274443654,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583416947,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583354019,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583400723,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
  "name": "superblock_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583486579,
      "name": "superblock_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:1963",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_path_notify",
        "security/selinux/hooks.c:selinux_umount",
        "security/selinux/hooks.c:selinux_mount",
        "security/selinux/hooks.c:selinux_sb_statfs",
        "security/selinux/hooks.c:selinux_sb_kern_mount",
        "security/selinux/hooks.c:selinux_quotactl",
        "security/selinux/hooks.c:selinux_quotactl"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int superblock_has_perm(const struct cred * cred, struct super_block * sb, u32 perms, struct common_audit_data * ad)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int superblock_has_perm(const struct cred * cred, struct super_block * sb, u32 perms, struct common_audit_data * ad)
```
</details>
</li>
</ul>
