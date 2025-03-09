# Function: <code>match_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int match_mnt(struct aa_profile * profile, const char * mntpnt, const char * devname, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575520,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:309",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_remount",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_new_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575520,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 847
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582818192,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:371",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582818192,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582914064,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914064,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582976401,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:373",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974912,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138592,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:375",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138592,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344544,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:375",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344544,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463184,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:376",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463184,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647600,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647600,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583753888,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753888,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145221,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143520,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584263605,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261904,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, const struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288709,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287104,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, const struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584674821,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673216,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, const struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585334389,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:357",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585332160,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int match_mnt(const struct cred * subj_cred, struct aa_profile * profile, const struct path * path, char * buffer, const struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586074953,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:365",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072560,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int match_mnt(const struct cred * subj_cred, struct aa_profile * profile, const struct path * path, char * buffer, const struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586310073,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:365",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586307648,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int match_mnt(const struct cred * subj_cred, struct aa_profile * profile, const struct path * path, char * buffer, const struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586566617,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:365",
      "file": "security/apparmor/mount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_remount"
      ],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_bind_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586564240,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495554024,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495554024,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228917136,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228917136,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289642592,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289642592,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274725276,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274725276,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722624,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722624,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659680,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659680,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583706400,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706400,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
int match_mnt(struct aa_profile * profile, const struct path * path, char * buffer, struct path * devpath, char * devbuffer, const char * type, long unsigned int flags, void * data, bool binary)
```

```json
{
  "name": "match_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583806688,
      "name": "match_mnt",
      "external": false,
      "loc": "security/apparmor/mount.c:372",
      "file": "security/apparmor/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/mount.c:aa_new_mount",
        "security/apparmor/mount.c:aa_move_mount",
        "security/apparmor/mount.c:aa_mount_change_type",
        "security/apparmor/mount.c:aa_bind_mount",
        "security/apparmor/mount.c:aa_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583806688,
      "name": "match_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<b>Param added. </b>
<code>const struct path * path</code>
</li>
<li>
<b>Param added. </b>
<code>char * buffer</code>
</li>
<li>
<b>Param added. </b>
<code>struct path * devpath</code>
</li>
<li>
<b>Param added. </b>
<code>char * devbuffer</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * mntpnt</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * devname</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, mntpnt, devname, type, flags, data, binary</code> ➡️ <code>profile, path, buffer, devpath, devbuffer, type, flags, data, binary</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * devpath</code> ➡️ <code>const struct path * devpath</code>
</li>
</ul>
</details>
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
<code>profile, path, buffer, devpath, devbuffer, type, flags, data, binary</code> ➡️ <code>subj_cred, profile, path, buffer, devpath, devbuffer, type, flags, data, binary</code>
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
