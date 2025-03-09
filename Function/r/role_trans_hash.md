# Function: <code>role_trans_hash</code>

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
u32 role_trans_hash(struct hashtab * h, const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833888,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:473",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833888,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583971336,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:495",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955376,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583998403,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:495",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982256,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584365363,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:495",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348992,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584990195,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:490",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971120,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705715,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:490",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685280,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585935971,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:490",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915536,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
u32 role_trans_hash(const void * k)
```

```json
{
  "name": "role_trans_hash",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586169728,
      "name": "role_trans_hash",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:483",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:policydb_roletr_search"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169728,
      "name": "role_trans_hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
u32 role_trans_hash(struct hashtab * h, const void * k)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct hashtab * h</code>
</li>
<li>
<b>Param reordered. </b>
<code>h, k</code> ➡️ <code>k</code>
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
