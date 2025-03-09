# Function: <code>configfs_make_dirent</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860464,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:225",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860464,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010352,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:225",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010352,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199168,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:225",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199168,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294384,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:225",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294384,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:238",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463581,
      "name": "configfs_make_dirent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582460160,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559552,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559552,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582866960,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866960,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939872,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939872,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967552,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:234",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967552,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303216,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:242",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303216,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809888,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:242",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809888,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584431152,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:242",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431152,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659904,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:242",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659904,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892656,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:242",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892656,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494202080,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494202080,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227635656,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227635656,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287894448,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287894448,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273662406,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273662406,
      "name": "configfs_make_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528288,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528288,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465456,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465456,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518768,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518768,
      "name": "configfs_make_dirent",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_make_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599344,
      "name": "configfs_make_dirent",
      "external": true,
      "loc": "fs/configfs/dir.c:236",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/file.c:configfs_create_bin_file",
        "fs/configfs/file.c:configfs_create_file",
        "fs/configfs/dir.c:configfs_create_link",
        "fs/configfs/dir.c:configfs_create_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599344,
      "name": "configfs_make_dirent",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int configfs_make_dirent(struct configfs_dirent * parent_sd, struct dentry * dentry, void * element, umode_t mode, int type)
```
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct configfs_fragment * frag</code>
</li>
</ul>
</details>
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
