# Function: <code>__aafs_ns_mkdir</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582892288,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1844",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892288,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 995
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583050624,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1908",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050624,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251232,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1905",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251232,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369248,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1903",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369248,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583556336,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1908",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583556336,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583662064,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662064,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584023232,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1995",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023232,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143168,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1995",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143168,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170320,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1996",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170320,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554976,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1996",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554976,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585197616,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:2016",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197616,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585927424,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:2205",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927424,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159632,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:2253",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159632,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586408880,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:2251",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408880,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495455000,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495455000,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228821968,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228821968,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289504816,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289504816,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1200
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274644054,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274644054,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630800,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630800,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567856,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567856,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614576,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614576,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```

```json
{
  "name": "__aafs_ns_mkdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712432,
      "name": "__aafs_ns_mkdir",
      "external": true,
      "loc": "security/apparmor/apparmorfs.c:1876",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:__aafs_ns_mkdir",
        "security/apparmor/policy_ns.c:__aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712432,
      "name": "__aafs_ns_mkdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __aafs_ns_mkdir(struct aa_ns * ns, struct dentry * parent, const char * name, struct dentry * dent)
```
</details>
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
