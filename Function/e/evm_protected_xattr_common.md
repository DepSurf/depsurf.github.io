# Function: <code>evm_protected_xattr_common</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int evm_protected_xattr_common(const char * req_xattr_name, bool all_xattrs)
```

```json
{
  "name": "evm_protected_xattr_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_protected_xattr_common",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:286",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_protect_xattr",
        "security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753440,
      "name": "evm_protected_xattr_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071592309959,
      "name": "evm_protected_xattr_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int evm_protected_xattr_common(const char * req_xattr_name, bool all_xattrs)
```

```json
{
  "name": "evm_protected_xattr_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_protected_xattr_common",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:286",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_init_security",
        "security/integrity/evm/evm_main.c:evm_protect_xattr",
        "security/integrity/evm/evm_main.c:evm_verifyxattr",
        "security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585435072,
      "name": "evm_protected_xattr_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071594092458,
      "name": "evm_protected_xattr_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int evm_protected_xattr_common(const char * req_xattr_name, bool all_xattrs)
```

```json
{
  "name": "evm_protected_xattr_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_protected_xattr_common",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:280",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_init_security",
        "security/integrity/evm/evm_main.c:evm_verifyxattr",
        "security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192304,
      "name": "evm_protected_xattr_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071596103248,
      "name": "evm_protected_xattr_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int evm_protected_xattr_common(const char * req_xattr_name, bool all_xattrs)
```

```json
{
  "name": "evm_protected_xattr_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_protected_xattr_common",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:280",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_init_security",
        "security/integrity/evm/evm_main.c:evm_verifyxattr",
        "security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586430016,
      "name": "evm_protected_xattr_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071596626354,
      "name": "evm_protected_xattr_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int evm_protected_xattr_common(const char * req_xattr_name, bool all_xattrs)
```

```json
{
  "name": "evm_protected_xattr_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_protected_xattr_common",
      "external": false,
      "loc": "security/integrity/evm/evm_main.c:294",
      "file": "security/integrity/evm/evm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_main.c:evm_inode_init_security",
        "security/integrity/evm/evm_main.c:evm_verifyxattr",
        "security/integrity/evm/evm_main.c:evm_protected_xattr_if_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586694240,
      "name": "evm_protected_xattr_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071597531996,
      "name": "evm_protected_xattr_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int evm_protected_xattr_common(const char * req_xattr_name, bool all_xattrs)
```
</details>
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
