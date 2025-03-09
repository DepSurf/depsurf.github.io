# Function: <code>aa_path_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488608,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/file.c:path_name",
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
      "addr": 18446744071582488608,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582721488,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
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
      "addr": 18446744071582721488,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 981
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816144,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
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
      "addr": 18446744071582816144,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 981
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903888,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903888,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583062000,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
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
      "addr": 18446744071583062000,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583264160,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583264160,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583382016,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:201",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583382016,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569520,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583569520,
      "name": "aa_path_name",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675296,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583675296,
      "name": "aa_path_name",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584038400,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038400,
      "name": "aa_path_name",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157536,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157536,
      "name": "aa_path_name",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184544,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184544,
      "name": "aa_path_name",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569568,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569568,
      "name": "aa_path_name",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215424,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215424,
      "name": "aa_path_name",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585947680,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947680,
      "name": "aa_path_name",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586180592,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586180592,
      "name": "aa_path_name",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586431872,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586431872,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495470208,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446603336495470208,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228836596,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:path_name",
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
      "addr": 3228836596,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289525056,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 13835058055289525056,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274657270,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446743936274657270,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644032,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583644032,
      "name": "aa_path_name",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583581088,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583581088,
      "name": "aa_path_name",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627808,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583627808,
      "name": "aa_path_name",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int aa_path_name(const struct path * path, int flags, char * buffer, const char * * name, const char * * info, const char * disconnected)
```

```json
{
  "name": "aa_path_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725872,
      "name": "aa_path_name",
      "external": true,
      "loc": "security/apparmor/path.c:197",
      "file": "security/apparmor/path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
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
      "addr": 18446744071583725872,
      "name": "aa_path_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
