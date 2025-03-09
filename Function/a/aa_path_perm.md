# Function: <code>aa_path_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_path_perm(const char * op, struct aa_label * label, struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549008,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:312",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549008,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789648,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:332",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789648,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582885152,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:332",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885152,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955104,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:335",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955104,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117216,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:329",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117216,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322928,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:329",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322928,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441440,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:330",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441440,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626480,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626480,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732656,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732656,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116096,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_truncate",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116096,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235120,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:315",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_truncate",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235120,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584260192,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:317",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584260192,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646144,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:317",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646144,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585303056,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:276",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303056,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int aa_path_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042368,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:403",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042368,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int aa_path_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277392,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:423",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277392,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int aa_path_perm(const char * op, const struct cred * subj_cred, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534112,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:430",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534112,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495529288,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495529288,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228895684,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228895684,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289609680,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289609680,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274706060,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274706060,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701392,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701392,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583638448,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583638448,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583685168,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685168,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int aa_path_perm(const char * op, struct aa_label * label, const struct path * path, int flags, u32 request, struct path_cond * cond)
```

```json
{
  "name": "aa_path_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583784912,
      "name": "aa_path_perm",
      "external": true,
      "loc": "security/apparmor/file.c:326",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_open",
        "security/apparmor/lsm.c:common_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784912,
      "name": "aa_path_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, label, path, flags, request, cond</code> ➡️ <code>op, subj_cred, label, path, flags, request, cond</code>
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
