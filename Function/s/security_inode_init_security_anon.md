# Function: <code>security_inode_init_security_anon</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```

```json
{
  "name": "security_inode_init_security_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879648,
      "name": "security_inode_init_security_anon",
      "external": true,
      "loc": "security/security.c:1277",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:__anon_inode_getfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879648,
      "name": "security_inode_init_security_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```

```json
{
  "name": "security_inode_init_security_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244576,
      "name": "security_inode_init_security_anon",
      "external": true,
      "loc": "security/security.c:1277",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:__anon_inode_getfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244576,
      "name": "security_inode_init_security_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```

```json
{
  "name": "security_inode_init_security_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851920,
      "name": "security_inode_init_security_anon",
      "external": true,
      "loc": "security/security.c:1297",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:__anon_inode_getfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851920,
      "name": "security_inode_init_security_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```

```json
{
  "name": "security_inode_init_security_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554864,
      "name": "security_inode_init_security_anon",
      "external": true,
      "loc": "security/security.c:1295",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:__anon_inode_getfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554864,
      "name": "security_inode_init_security_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```

```json
{
  "name": "security_inode_init_security_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585785760,
      "name": "security_inode_init_security_anon",
      "external": true,
      "loc": "security/security.c:1803",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:__anon_inode_getfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785760,
      "name": "security_inode_init_security_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```

```json
{
  "name": "security_inode_init_security_anon",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586033904,
      "name": "security_inode_init_security_anon",
      "external": true,
      "loc": "security/security.c:1876",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/anon_inodes.c:__anon_inode_getfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033904,
      "name": "security_inode_init_security_anon",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int security_inode_init_security_anon(struct inode * inode, const struct qstr * name, const struct inode * context_inode)
```
</details>
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
