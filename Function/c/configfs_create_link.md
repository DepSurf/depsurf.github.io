# Function: <code>configfs_create_link</code>

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
int configfs_create_link(struct configfs_symlink * sl, struct dentry * parent, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863728,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:350",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863728,
      "name": "configfs_create_link",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_symlink * sl, struct dentry * parent, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013632,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:350",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013632,
      "name": "configfs_create_link",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_symlink * sl, struct dentry * parent, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201984,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:350",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201984,
      "name": "configfs_create_link",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_symlink * sl, struct dentry * parent, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582297104,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:350",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297104,
      "name": "configfs_create_link",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int configfs_create_link(struct configfs_symlink * sl, struct dentry * parent, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:365",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463619,
      "name": "configfs_create_link.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582463232,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562528,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562528,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870432,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870432,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943344,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:355",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943344,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970928,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:353",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970928,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306528,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:361",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306528,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813328,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:361",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813328,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434816,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:362",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434816,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663552,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:362",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663552,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896256,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:362",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896256,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494205656,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494205656,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227639124,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227639124,
      "name": "configfs_create_link",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287900608,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287900608,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273666136,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:configfs_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273666136,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531264,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531264,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468432,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468432,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521744,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521744,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_dirent * target, struct dentry * parent, struct dentry * dentry, char * body)
```

```json
{
  "name": "configfs_create_link",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602432,
      "name": "configfs_create_link",
      "external": true,
      "loc": "fs/configfs/dir.c:354",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/symlink.c:create_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602432,
      "name": "configfs_create_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int configfs_create_link(struct configfs_symlink * sl, struct dentry * parent, struct dentry * dentry)
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct configfs_dirent * target</code>
</li>
<li>
<b>Param added. </b>
<code>char * body</code>
</li>
<li>
<b>Param removed. </b>
<code>struct configfs_symlink * sl</code>
</li>
</ul>
</details>
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
