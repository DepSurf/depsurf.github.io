# Function: <code>security_path_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_path_rename(struct path * old_dir, struct dentry * old_dentry, struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582238512,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:464",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238512,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457200,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:465",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457200,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582549664,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:474",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549664,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633984,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1079",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633984,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787712,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1028",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787712,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984528,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:570",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984528,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096304,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1091",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096304,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284432,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1105",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284432,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390192,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390192,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728160,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1293",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728160,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848352,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1295",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848352,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873904,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1345",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873904,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237968,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1348",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237968,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584844320,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1365",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584844320,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546384,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1363",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585546384,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776848,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1933",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776848,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025840,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:2006",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025840,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495140768,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495140768,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228528604,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228528604,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289058032,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289058032,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274390518,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274390518,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358928,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358928,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296032,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296032,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342704,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342704,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_path_rename(const struct path * old_dir, struct dentry * old_dentry, const struct path * new_dir, struct dentry * new_dentry, unsigned int flags)
```

```json
{
  "name": "security_path_rename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437888,
      "name": "security_path_rename",
      "external": true,
      "loc": "security/security.c:1145",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_renameat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437888,
      "name": "security_path_rename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
<code>struct path * old_dir</code> ➡️ <code>const struct path * old_dir</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path * new_dir</code> ➡️ <code>const struct path * new_dir</code>
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
