# Function: <code>id_permitted_for_cred</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:156",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281920,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071591368805,
      "name": "id_permitted_for_cred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:153",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584307152,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071591311479,
      "name": "id_permitted_for_cred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:153",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584693696,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071592307118,
      "name": "id_permitted_for_cred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:153",
      "file": "security/safesetid/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357216,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071594088719,
      "name": "id_permitted_for_cred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586106076,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:148",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups"
      ],
      "caller_func": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106672,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586344713,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:148",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups"
      ],
      "caller_func": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345296,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
```

```json
{
  "name": "id_permitted_for_cred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586611570,
      "name": "id_permitted_for_cred",
      "external": false,
      "loc": "security/safesetid/lsm.c:148",
      "file": "security/safesetid/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups"
      ],
      "caller_func": [
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586612208,
      "name": "id_permitted_for_cred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
bool id_permitted_for_cred(const struct cred * old, kid_t new_id, enum setid_type new_type)
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
