# Function: <code>hashtab_init</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int hashtab_init(struct hashtab * h, u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823488,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:32",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823488,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583944640,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:31",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944640,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971632,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:31",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971632,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:31",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592297215,
      "name": "hashtab_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584337184,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:32",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594078857,
      "name": "hashtab_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584958240,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:32",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596095973,
      "name": "hashtab_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585671232,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:32",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596619188,
      "name": "hashtab_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585900992,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int hashtab_init(struct hashtab * h, u32 nel_hint)
```

```json
{
  "name": "hashtab_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hashtab_init",
      "external": true,
      "loc": "security/selinux/ss/hashtab.c:32",
      "file": "security/selinux/ss/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/symtab.c:symtab_init",
        "security/selinux/ss/policydb.c:policydb_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:filename_trans_read",
        "security/selinux/ss/policydb.c:range_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597524888,
      "name": "hashtab_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586149456,
      "name": "hashtab_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int hashtab_init(struct hashtab * h, u32 (*)(struct hashtab *, const void *) hash_value, int (*)(struct hashtab *, const void *, const void *) keycmp, u32 nel_hint)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 (*)(struct hashtab *, const void *) hash_value</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*)(struct hashtab *, const void *, const void *) keycmp</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, hash_value, keycmp, nel_hint</code> ➡️ <code>h, nel_hint</code>
</li>
</ul>
</details>
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
