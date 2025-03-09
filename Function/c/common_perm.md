# Function: <code>common_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int common_perm(const char * op, struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536624,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:189",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_truncate",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536624,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776000,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:189",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776000,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871136,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:189",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871136,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582942400,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:171",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582942400,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103200,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:171",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103200,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307712,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:200",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307712,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426640,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:195",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426640,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612240,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612240,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718416,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718416,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584099420,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:204",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_truncate",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584217116,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:204",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_truncate",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584243305,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:204",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584629401,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:204",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585288125,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:215",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586025533,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:233",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586260953,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:233",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
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
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586515068,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:230",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_path_symlink",
        "security/apparmor/lsm.c:apparmor_path_mknod",
        "security/apparmor/lsm.c:apparmor_path_rmdir",
        "security/apparmor/lsm.c:apparmor_path_mkdir",
        "security/apparmor/lsm.c:apparmor_path_unlink",
        "security/apparmor/lsm.c:common_perm_cond"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495513760,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495513760,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228882420,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228882420,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289585696,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289585696,
      "name": "common_perm",
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274693412,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274693412,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687152,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687152,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624208,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624208,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670928,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670928,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```

```json
{
  "name": "common_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769536,
      "name": "common_perm",
      "external": false,
      "loc": "security/apparmor/lsm.c:191",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:common_perm_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769536,
      "name": "common_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int common_perm(const char * op, const struct path * path, u32 mask, struct path_cond * cond)
```
</details>
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
