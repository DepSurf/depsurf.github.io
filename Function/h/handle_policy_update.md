# Function: <code>handle_policy_update</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583667429,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583773701,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164144,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071584164985,
      "name": "handle_policy_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283280,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071591369010,
      "name": "handle_policy_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584308000,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 923
    },
    {
      "addr": 18446744071591311552,
      "name": "handle_policy_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694560,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
    },
    {
      "addr": 18446744071592307191,
      "name": "handle_policy_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358192,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    },
    {
      "addr": 18446744071594088753,
      "name": "handle_policy_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107760,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107760,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586346384,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346384,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len, enum setid_type policy_type)
```

```json
{
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586613296,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:139",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_write",
        "security/safesetid/securityfs.c:safesetid_uid_file_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586613296,
      "name": "handle_policy_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1310
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495575312,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228937372,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289671104,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274742532,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583742437,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583679493,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583726213,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
  "name": "handle_policy_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583826965,
      "name": "handle_policy_update",
      "external": false,
      "loc": "security/safesetid/securityfs.c:110",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/safesetid/securityfs.c:safesetid_file_write"
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
ssize_t handle_policy_update(struct file * file, const char * ubuf, size_t len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum setid_type policy_type</code>
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
