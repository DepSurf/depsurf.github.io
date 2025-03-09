# Function: <code>map_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018288,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:600",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_uid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_projid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018288,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1649
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050880,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:600",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050880,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1663
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090544,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:646",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090544,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1660
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096192,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:647",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096192,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1747
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148848,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:855",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148848,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1859
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:856",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208960,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1774
    },
    {
      "addr": 18446744071580212382,
      "name": "map_write.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:856",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261216,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1929
    },
    {
      "addr": 18446744071580264814,
      "name": "map_write.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312240,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071580315678,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361072,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071580364510,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433984,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1866
    },
    {
      "addr": 18446744071580437822,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421024,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1866
    },
    {
      "addr": 18446744071591315609,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:905",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425632,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1636
    },
    {
      "addr": 18446744071591257849,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:921",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589408,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1663
    },
    {
      "addr": 18446744071592162177,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:926",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791376,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1893
    },
    {
      "addr": 18446744071593935219,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076208,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:926",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076208,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1718
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167408,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:926",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167408,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1831
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271840,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:929",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271840,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1831
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491621960,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491621960,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225577596,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225577596,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1636
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284614992,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284614992,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1960
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
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272022304,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272022304,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329872,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071580333310,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277136,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071580280574,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321120,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071580324558,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
ssize_t map_write(struct file * file, const char * buf, size_t count, loff_t * ppos, int cap_setid, struct uid_gid_map * map, struct uid_gid_map * parent_map)
```

```json
{
  "name": "map_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_write",
      "external": false,
      "loc": "kernel/user_namespace.c:850",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:proc_projid_map_write",
        "kernel/user_namespace.c:proc_gid_map_write",
        "kernel/user_namespace.c:proc_uid_map_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376144,
      "name": "map_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071580379582,
      "name": "map_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
