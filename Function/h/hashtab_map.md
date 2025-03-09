# Function: <code>hashtab_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312016,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:120",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312016,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582533184,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:120",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533184,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626000,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:120",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626000,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717936,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:120",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717936,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873824,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873824,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072080,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072080,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185584,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185584,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372816,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372816,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478768,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478768,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824208,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:125",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824208,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583944976,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:78",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_destroy_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944976,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971968,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:78",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_destroy_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971968,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584337568,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:85",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337568,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584958656,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:86",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958656,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671696,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:86",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671696,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585901456,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:86",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901456,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586149920,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:86",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:common_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/conditional.c:cond_policydb_dup",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586149920,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495243640,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495243640,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228625416,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228625416,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289210512,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289210512,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274469432,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274469432,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447504,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447504,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384576,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384576,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583431280,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583431280,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int hashtab_map(struct hashtab * h, int (*)(void *, void *, void *) apply, void * args)
```

```json
{
  "name": "hashtab_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583527552,
      "name": "hashtab_map",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:123",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:policydb_write",
        "security/selinux/ss/policydb.c:class_write",
        "security/selinux/ss/policydb.c:common_write",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_destroy",
        "security/selinux/ss/policydb.c:policydb_index",
        "security/selinux/ss/policydb.c:cls_destroy",
        "security/selinux/ss/policydb.c:common_destroy",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527552,
      "name": "hashtab_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
