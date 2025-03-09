# Function: <code>match_mnt_path_str</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817056,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:319",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817056,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912912,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:319",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912912,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582973968,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:319",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973968,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 930
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137616,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:318",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137616,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343584,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:318",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343584,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462224,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:319",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462224,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583646688,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583646688,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752976,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752976,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143120,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143120,
      "name": "match_mnt_path_str",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261504,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261504,
      "name": "match_mnt_path_str",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286704,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286704,
      "name": "match_mnt_path_str",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584672784,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672784,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331696,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:298",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331696,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int match_mnt_path_str(const struct cred * subj_cred, struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586072064,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:303",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072064,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int match_mnt_path_str(const struct cred * subj_cred, struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586307152,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:303",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586307152,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int match_mnt_path_str(const struct cred * subj_cred, struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563744,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:303",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563744,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495553184,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495553184,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228916308,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228916308,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289641536,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289641536,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274724486,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274724486,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721712,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721712,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658768,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658768,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583705488,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705488,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```

```json
{
  "name": "match_mnt_path_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583805776,
      "name": "match_mnt_path_str",
      "external": false,
      "loc": "security/apparmor/mount.c:315",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805776,
      "name": "match_mnt_path_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int match_mnt_path_str(struct aa_profile * profile, const struct path * mntpath, char * buffer, const char * devname, const char * type, long unsigned int flags, void * data, bool binary, const char * devinfo)
```
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, mntpath, buffer, devname, type, flags, data, binary, devinfo</code> ➡️ <code>subj_cred, profile, mntpath, buffer, devname, type, flags, data, binary, devinfo</code>
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
