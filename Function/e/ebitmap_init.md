# Function: <code>ebitmap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308115,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_cpy",
        "security/selinux/ss/ebitmap.c:ebitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582329175,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369079,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582531036,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557209,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582590217,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582623836,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582650415,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582683449,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582715685,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741928,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582776284,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:59",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582871573,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897936,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932348,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583069797,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098442,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132021,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/mls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_convert_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583183285,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213003,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583370597,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397420,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583476549,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583503308,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821733,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583852290,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834736,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583943109,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583975241,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956176,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583970053,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002306,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982912,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584335557,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584369498,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349648,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584956503,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584994643,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973104,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669431,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585710675,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688464,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899191,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585940931,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585921376,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ebitmap_init(struct ebitmap * e)
```

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586147655,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_and",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586189593,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read_helper_compat",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169248,
      "name": "ebitmap_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495241368,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495270828,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228623004,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 3228652616,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:read_cons_helper",
        "security/selinux/ss/policydb.c:read_cons_helper"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289207384,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289249108,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274467000,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274494420,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583445285,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472044,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583382357,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583409116,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583429061,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455820,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ebitmap_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583525333,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/ebitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/ebitmap.c:ebitmap_read",
        "security/selinux/ss/ebitmap.c:ebitmap_cpy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583552044,
      "name": "ebitmap_init",
      "external": false,
      "loc": "security/selinux/ss/ebitmap.h:60",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ebitmap_init(struct ebitmap * e)
```
</details>
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
