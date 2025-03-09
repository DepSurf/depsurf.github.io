# Function: <code>ebitmap_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582309808,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:343",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309808,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531008,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:343",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531008,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 734
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582623808,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:343",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623808,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715680,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:345",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715680,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871568,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871568,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071154,
      "name": "ebitmap_read.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071583069760,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184642,
      "name": "ebitmap_read.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071583183248,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371866,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583370592,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477818,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583476544,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823264,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583821696,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591364230,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071583943072,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591307216,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071583970016,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592297038,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071584335520,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 707
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:364",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594078706,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071584956432,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669360,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669360,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899120,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899120,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586147584,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:365",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147584,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495241336,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495241336,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228622960,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228622960,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289207360,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289207360,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274466956,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274466956,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446554,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583445280,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383626,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583382352,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430330,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583429056,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int ebitmap_read(struct ebitmap * e, void * fp)
```

```json
{
  "name": "ebitmap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ebitmap_read",
      "external": true,
      "loc": "security/selinux/ss/ebitmap.c:346",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:user_read",
        "security/selinux/ss/policydb.c:mls_read_level",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:role_read",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper",
        "security/selinux/ss/policydb.c:mls_read_range_helper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526602,
      "name": "ebitmap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583525328,
      "name": "ebitmap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
