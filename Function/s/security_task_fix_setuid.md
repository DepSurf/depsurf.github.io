# Function: <code>security_task_fix_setuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245968,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:923",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setfsuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245968,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464608,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:947",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464608,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557072,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:968",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557072,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644352,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1605",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644352,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582798944,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1567",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582798944,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995760,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1071",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995760,
      "name": "security_task_fix_setuid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107936,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1679",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107936,
      "name": "security_task_fix_setuid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294224,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1698",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294224,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583399328,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399328,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738848,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1921",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738848,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859168,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1938",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859168,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583885344,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1988",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885344,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249056,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1996",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249056,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858784,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:2001",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858784,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585563120,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:2048",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563120,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794112,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:3296",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794112,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042384,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:3368",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042384,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495151792,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495151792,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228539400,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228539400,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289077472,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289077472,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274398928,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274398928,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368064,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368064,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305168,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305168,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351840,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351840,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int security_task_fix_setuid(struct cred * new, const struct cred * old, int flags)
```

```json
{
  "name": "security_task_fix_setuid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447024,
      "name": "security_task_fix_setuid",
      "external": true,
      "loc": "security/security.c:1737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447024,
      "name": "security_task_fix_setuid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
