# Function: <code>common_perm_cond</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582537141,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:203",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_truncate",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776528,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:203",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776528,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871664,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:203",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871664,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582942656,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:193",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582942656,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103504,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:193",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103504,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308000,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:222",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308000,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426944,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:217",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426944,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583612512,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612512,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718688,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718688,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:226",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
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
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:226",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244880,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:226",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244880,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630560,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:226",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630560,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585290144,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:237",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290144,
      "name": "common_perm_cond",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027968,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:256",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_file_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027968,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262256,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:256",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_file_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262256,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586515408,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:253",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_file_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586515408,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495514080,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495514080,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228882740,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228882740,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289586080,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289586080,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274693626,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274693626,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687424,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687424,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624480,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624480,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583671200,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671200,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```

```json
{
  "name": "common_perm_cond",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769888,
      "name": "common_perm_cond",
      "external": false,
      "loc": "security/apparmor/lsm.c:213",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inode_getattr",
        "security/apparmor/lsm.c:apparmor_path_chown",
        "security/apparmor/lsm.c:apparmor_path_chmod",
        "security/apparmor/lsm.c:apparmor_path_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769888,
      "name": "common_perm_cond",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int common_perm_cond(const char * op, const struct path * path, u32 mask)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int common_perm_cond(const char * op, const struct path * path, u32 mask)
```
</details>
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
