# Function: <code>hashtab_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311232,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:12",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311232,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532416,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:12",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532416,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625232,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:12",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625232,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717136,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:12",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717136,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873024,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873024,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583071280,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583071280,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184768,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184768,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372016,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372016,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477968,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477968,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495242784,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495242784,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228624560,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228624560,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289209232,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289209232,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274468686,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274468686,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446704,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446704,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583383776,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383776,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430480,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430480,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```

```json
{
  "name": "hashtab_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526752,
      "name": "hashtab_create",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:15",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526752,
      "name": "hashtab_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct hashtab * hashtab_create(u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 size)
```
</details>
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
