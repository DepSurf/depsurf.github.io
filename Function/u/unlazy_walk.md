# Function: <code>unlazy_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037744,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:680",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:path_mountpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037744,
      "name": "unlazy_walk",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198064,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198064,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int unlazy_walk(struct nameidata * nd, struct dentry * dentry, unsigned int seq)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275328,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:685",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275328,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323888,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:683",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323888,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464048,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:684",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464048,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620864,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:668",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:link_path_walk",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620864,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707248,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:668",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707248,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826000,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:666",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826000,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898624,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898624,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126096,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:682",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126096,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493378512,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493378512,
      "name": "unlazy_walk",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226964716,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226964716,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286931168,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286931168,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273095930,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273095930,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867360,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867360,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804960,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804960,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858672,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858672,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int unlazy_walk(struct nameidata * nd)
```

```json
{
  "name": "unlazy_walk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930016,
      "name": "unlazy_walk",
      "external": false,
      "loc": "fs/namei.c:672",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:pick_link",
        "fs/namei.c:lookup_fast",
        "fs/namei.c:complete_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930016,
      "name": "unlazy_walk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dentry * dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int seq</code>
</li>
</ul>
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int unlazy_walk(struct nameidata * nd)
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
