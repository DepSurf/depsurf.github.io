# Function: <code>audit_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int audit_mount(struct aa_profile * profile, const char * op, const char * name, const char * src_name, const char * type, const char * trans, long unsigned int flags, const void * data, u32 request, struct aa_perms * perms, const char * info, int error)
```

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573920,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:133",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573920,
      "name": "audit_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
int audit_mount(struct aa_profile * profile, const char * op, const char * name, const char * src_name, const char * type, const char * trans, long unsigned int flags, const void * data, u32 request, struct aa_perms * perms, const char * info, int error)
```

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815472,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:133",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815472,
      "name": "audit_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int audit_mount(struct aa_profile * profile, const char * op, const char * name, const char * src_name, const char * type, const char * trans, long unsigned int flags, const void * data, u32 request, struct aa_perms * perms, const char * info, int error)
```

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911328,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:133",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911328,
      "name": "audit_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582973600,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:133",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973600,
      "name": "audit_mount.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583137248,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:133",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137248,
      "name": "audit_mount.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583343216,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:133",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343216,
      "name": "audit_mount.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583461856,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:134",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461856,
      "name": "audit_mount.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583646320,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583646320,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583752608,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752608,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584141568,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141568,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584259952,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259952,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584285536,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285536,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584671616,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584671616,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585331264,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331264,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586071648,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:132",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586071648,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586306736,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:132",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306736,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586563328,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:132",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563328,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495552768,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495552768,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228915868,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228915868,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289640928,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289640928,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274724152,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274724152,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721344,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721344,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583658400,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658400,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583705120,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705120,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_mount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583805408,
      "name": "audit_mount",
      "external": false,
      "loc": "security/apparmor/mount.c:130",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805408,
      "name": "audit_mount.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int audit_mount(struct aa_profile * profile, const char * op, const char * name, const char * src_name, const char * type, const char * trans, long unsigned int flags, const void * data, u32 request, struct aa_perms * perms, const char * info, int error)
```
</details>
</li>
</ul>
