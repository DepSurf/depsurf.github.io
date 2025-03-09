# Function: <code>aafs_remove</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582892190,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:347",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879984,
      "name": "aafs_remove.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583050565,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:348",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035744,
      "name": "aafs_remove.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583251132,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:345",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236336,
      "name": "aafs_remove.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583369148,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:345",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353920,
      "name": "aafs_remove.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540224,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:350",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540224,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583645952,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645952,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003424,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:348",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003424,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123200,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:348",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123200,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150704,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:348",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150704,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534544,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:348",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534544,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175040,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:351",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175040,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902848,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:352",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902848,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586134000,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:353",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134000,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586383232,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:353",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_create_rawdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586383232,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495437648,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495437648,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228805484,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228805484,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289481088,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289481088,
      "name": "aafs_remove",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274630214,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274630214,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614688,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614688,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551744,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551744,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598464,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598464,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void aafs_remove(struct dentry * dentry)
```

```json
{
  "name": "aafs_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695552,
      "name": "aafs_remove",
      "external": false,
      "loc": "security/apparmor/apparmorfs.c:318",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_rmdir",
        "security/apparmor/apparmorfs.c:remove_rawdata_dents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695552,
      "name": "aafs_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void aafs_remove(struct dentry * dentry)
```
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
