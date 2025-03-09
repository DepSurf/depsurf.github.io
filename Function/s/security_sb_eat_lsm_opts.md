# Function: <code>security_sb_eat_lsm_opts</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094896,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:864",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:mount_fs",
        "fs/namespace.c:do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094896,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279696,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:873",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279696,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385712,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385712,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724032,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1055",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724032,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844224,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1057",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844224,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583869984,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1095",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869984,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233760,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1095",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233760,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584839248,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1107",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839248,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585540496,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1105",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540496,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771152,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1409",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771152,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586019584,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:1462",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:vfs_parse_monolithic_sep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586019584,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495135232,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495135232,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228523244,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228523244,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289047792,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289047792,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274386468,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274386468,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354448,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354448,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291552,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291552,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583338224,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338224,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```

```json
{
  "name": "security_sb_eat_lsm_opts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433408,
      "name": "security_sb_eat_lsm_opts",
      "external": true,
      "loc": "security/security.c:907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_parse_options",
        "fs/fs_context.c:legacy_parse_monolithic",
        "fs/fs_context.c:generic_parse_monolithic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433408,
      "name": "security_sb_eat_lsm_opts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int security_sb_eat_lsm_opts(char * options, void * * mnt_opts)
```
</details>
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
