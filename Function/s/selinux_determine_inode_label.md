# Function: <code>selinux_determine_inode_label</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260752,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1738",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:may_create",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:selinux_inode_init_security"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260752,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int selinux_determine_inode_label(struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489344,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1811",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489344,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582589664,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1820",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589664,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582681024,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1809",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582681024,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582836464,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1823",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836464,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583039296,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1926",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039296,
      "name": "selinux_determine_inode_label",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583154000,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1740",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154000,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583340784,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1784",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340784,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583446160,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446160,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788944,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1739",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788944,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583911024,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1748",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583911024,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939136,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1807",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939136,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304832,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1799",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304832,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919936,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1737",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919936,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628816,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1736",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628816,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585858832,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1746",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858832,
      "name": "selinux_determine_inode_label",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586108576,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108576,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495207304,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495207304,
      "name": "selinux_determine_inode_label.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228587200,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228587200,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289150864,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289150864,
      "name": "selinux_determine_inode_label.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274441952,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274441952,
      "name": "selinux_determine_inode_label.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583414896,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414896,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583351968,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351968,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583398672,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398672,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```

```json
{
  "name": "selinux_determine_inode_label",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583484528,
      "name": "selinux_determine_inode_label",
      "external": false,
      "loc": "security/selinux/hooks.c:1786",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_init_security",
        "security/selinux/hooks.c:selinux_dentry_create_files_as",
        "security/selinux/hooks.c:selinux_dentry_init_security",
        "security/selinux/hooks.c:may_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583484528,
      "name": "selinux_determine_inode_label",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
<code>const struct inode * dir</code> ➡️ <code>struct inode * dir</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct task_security_struct * tsec</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, name, tclass, _new_isid</code> ➡️ <code>tsec, dir, name, tclass, _new_isid</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct * tsec, struct inode * dir, const struct qstr * name, u16 tclass, u32 * _new_isid)
```
</details>
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
