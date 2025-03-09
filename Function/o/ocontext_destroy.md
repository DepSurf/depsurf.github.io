# Function: <code>ocontext_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ocontext_destroy(struct ocontext * c, int i)
```

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582325936,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:776",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325936,
      "name": "ocontext_destroy",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ocontext_destroy(struct ocontext * c, int i)
```

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547120,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:776",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547120,
      "name": "ocontext_destroy",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ocontext_destroy(struct ocontext * c, int i)
```

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639968,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:776",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639968,
      "name": "ocontext_destroy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582739696,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:780",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582728272,
      "name": "ocontext_destroy.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582895698,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:780",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884256,
      "name": "ocontext_destroy.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583097768,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:780",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081904,
      "name": "ocontext_destroy.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583212791,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:783",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197664,
      "name": "ocontext_destroy.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583396638,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:744",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383904,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583502526,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489792,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583851854,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:367",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835520,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583974798,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:367",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957168,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584001870,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:367",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984032,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584369038,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:367",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350768,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994117,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:362",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973728,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585709515,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:362",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689040,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585939787,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:362",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922384,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586188403,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:362",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586170448,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495269948,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495256520,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228651780,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228637452,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289247272,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289229280,
      "name": "ocontext_destroy.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274496900,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274488740,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583471262,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583458528,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583408334,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583395600,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583455038,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442304,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
  "name": "ocontext_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583551262,
      "name": "ocontext_destroy",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:355",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:genfs_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538560,
      "name": "ocontext_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void ocontext_destroy(struct ocontext * c, int i)
```
</details>
</li>
</ul>
