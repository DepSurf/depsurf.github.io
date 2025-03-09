# Function: <code>smk_fetch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582388240,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:261",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388240,
      "name": "smk_fetch.isra.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598144,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:261",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598144,
      "name": "smk_fetch",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582703008,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:261",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702512,
      "name": "smk_fetch.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582788929,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:262",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788448,
      "name": "smk_fetch.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582945281,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:262",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944800,
      "name": "smk_fetch.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583145677,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:262",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145200,
      "name": "smk_fetch.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583262363,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:280",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261872,
      "name": "smk_fetch.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449973,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449504,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583555909,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555440,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583906758,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:278",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583906160,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584025990,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:278",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025392,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584053840,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:278",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053840,
      "name": "smk_fetch",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584425488,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:278",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425488,
      "name": "smk_fetch",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585054832,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054832,
      "name": "smk_fetch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774880,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:282",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774880,
      "name": "smk_fetch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586007200,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:282",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007200,
      "name": "smk_fetch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586253760,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:292",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253760,
      "name": "smk_fetch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495329184,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495328672,
      "name": "smk_fetch.part.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228707220,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228706696,
      "name": "smk_fetch.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289330232,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289329488,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274550454,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274550044,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524645,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524176,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583461701,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461232,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583508421,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507952,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "smk_fetch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583604917,
      "name": "smk_fetch",
      "external": false,
      "loc": "security/smack/smack_lsm.c:281",
      "file": "security/smack/smack_lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate",
        "security/smack/smack_lsm.c:smack_d_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604448,
      "name": "smk_fetch.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct smack_known * smk_fetch(const char * name, struct inode * ip, struct dentry * dp)
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
