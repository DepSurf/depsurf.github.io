# Function: <code>path_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int path_flags(struct aa_profile * profile, struct path * path)
```

```json
{
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573776,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:333",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573776,
      "name": "path_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int path_flags(struct aa_profile * profile, const struct path * path)
```

```json
{
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815328,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:296",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815328,
      "name": "path_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int path_flags(struct aa_profile * profile, const struct path * path)
```

```json
{
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911184,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:296",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911184,
      "name": "path_flags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582975276,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:296",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583138986,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:295",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583344961,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:295",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583463601,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:296",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583648033,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583754321,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584143937,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584262321,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584287506,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584673618,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585333012,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:275",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586073493,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:279",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586308600,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:279",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586565158,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:279",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495554432,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228917512,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289643124,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274725566,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583723057,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583660113,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583706833,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
  "name": "path_flags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583807121,
      "name": "path_flags",
      "external": false,
      "loc": "security/apparmor/mount.c:292",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt_path_str"
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int path_flags(struct aa_profile * profile, const struct path * path)
```
</details>
</li>
</ul>
