# Function: <code>cond_policydb_destroy_dup</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584006944,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:737",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006944,
      "name": "cond_policydb_destroy_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584034544,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:737",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034544,
      "name": "cond_policydb_destroy_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584405952,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:740",
      "file": "security/selinux/ss/conditional.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405632,
      "name": "cond_policydb_destroy_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585032801,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:738",
      "file": "security/selinux/ss/conditional.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032480,
      "name": "cond_policydb_destroy_dup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585751281,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:738",
      "file": "security/selinux/ss/conditional.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750944,
      "name": "cond_policydb_destroy_dup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585981953,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:738",
      "file": "security/selinux/ss/conditional.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585981616,
      "name": "cond_policydb_destroy_dup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cond_policydb_destroy_dup(struct policydb * p)
```

```json
{
  "name": "cond_policydb_destroy_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586229281,
      "name": "cond_policydb_destroy_dup",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:738",
      "file": "security/selinux/ss/conditional.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/conditional.c:cond_policydb_dup"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228944,
      "name": "cond_policydb_destroy_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void cond_policydb_destroy_dup(struct policydb * p)
```
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
