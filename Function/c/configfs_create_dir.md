# Function: <code>configfs_create_dir</code>

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
int configfs_create_dir(struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860560,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:278",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860560,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010448,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:278",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010448,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199264,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:278",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199264,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294480,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:278",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294480,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:291",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460256,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    },
    {
      "addr": 18446744071582463600,
      "name": "configfs_create_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559648,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559648,
      "name": "configfs_create_dir",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582867056,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:create_default_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867056,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939968,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:276",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/configfs/dir.c:create_default_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939968,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967648,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:274",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967648,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303312,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:282",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303312,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583810000,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:282",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583810000,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584431280,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:282",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584431280,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660032,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:282",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660032,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892784,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:282",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892784,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494202264,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494202264,
      "name": "configfs_create_dir",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227635804,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227635804,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287894656,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287894656,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273662526,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273662526,
      "name": "configfs_create_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528384,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528384,
      "name": "configfs_create_dir",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465552,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465552,
      "name": "configfs_create_dir",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518864,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518864,
      "name": "configfs_create_dir",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item * item, struct dentry * dentry, struct configfs_fragment * frag)
```

```json
{
  "name": "configfs_create_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599440,
      "name": "configfs_create_dir",
      "external": false,
      "loc": "fs/configfs/dir.c:275",
      "file": "fs/configfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/configfs/dir.c:configfs_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599440,
      "name": "configfs_create_dir",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int configfs_create_dir(struct config_item * item, struct dentry * dentry)
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
