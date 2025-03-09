# Function: <code>set_cred_ucounts</code>

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
int set_cred_ucounts(struct cred * new)
```

```json
{
  "name": "set_cred_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715776,
      "name": "set_cred_ucounts",
      "external": true,
      "loc": "kernel/cred.c:668",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/cred.c:copy_creds",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715776,
      "name": "set_cred_ucounts",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_cred_ucounts(struct cred * new)
```

```json
{
  "name": "set_cred_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579794376,
      "name": "set_cred_ucounts",
      "external": true,
      "loc": "kernel/cred.c:666",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794528,
      "name": "set_cred_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int set_cred_ucounts(struct cred * new)
```

```json
{
  "name": "set_cred_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579901547,
      "name": "set_cred_ucounts",
      "external": true,
      "loc": "kernel/cred.c:666",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901696,
      "name": "set_cred_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int set_cred_ucounts(struct cred * new)
```

```json
{
  "name": "set_cred_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053624,
      "name": "set_cred_ucounts",
      "external": true,
      "loc": "kernel/cred.c:666",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053792,
      "name": "set_cred_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int set_cred_ucounts(struct cred * new)
```

```json
{
  "name": "set_cred_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108056,
      "name": "set_cred_ucounts",
      "external": true,
      "loc": "kernel/cred.c:666",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108224,
      "name": "set_cred_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int set_cred_ucounts(struct cred * new)
```

```json
{
  "name": "set_cred_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153085,
      "name": "set_cred_ucounts",
      "external": true,
      "loc": "kernel/cred.c:583",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:copy_creds"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/user_namespace.c:userns_install",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153232,
      "name": "set_cred_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int set_cred_ucounts(struct cred * new)
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
