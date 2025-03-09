# Function: <code>uid_hash_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420368,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:112",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:find_user",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420368,
      "name": "uid_hash_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432784,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:112",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432784,
      "name": "uid_hash_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453136,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:112",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453136,
      "name": "uid_hash_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441072,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:113",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441072,
      "name": "uid_hash_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469376,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:119",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469376,
      "name": "uid_hash_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579483504,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:120",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483504,
      "name": "uid_hash_find.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579516768,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:120",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516768,
      "name": "uid_hash_find.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579536464,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536464,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562528,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562528,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579594512,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594512,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579574480,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574480,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580176,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580176,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579654320,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:118",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654320,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579750032,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:118",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750032,
      "name": "uid_hash_find.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882064,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:118",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882064,
      "name": "uid_hash_find.isra.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931216,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:118",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931216,
      "name": "uid_hash_find.isra.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970528,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:131",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970528,
      "name": "uid_hash_find.isra.0",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490721808,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490721808,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```

```json
{
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224777540,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224777540,
      "name": "uid_hash_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283545208,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271437584,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538832,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538832,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579467600,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467600,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579536112,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536112,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "uid_hash_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569168,
      "name": "uid_hash_find",
      "external": false,
      "loc": "kernel/user.c:121",
      "file": "kernel/user.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:alloc_uid",
        "kernel/user.c:alloc_uid",
        "kernel/user.c:find_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569168,
      "name": "uid_hash_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct user_struct * uid_hash_find(kuid_t uid, struct hlist_head * hashent)
```
</details>
</li>
</ul>
