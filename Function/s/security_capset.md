# Function: <code>security_capset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240000,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:175",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240000,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458672,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:176",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458672,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551136,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:176",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551136,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638032,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:747",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638032,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792016,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:697",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:SyS_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792016,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990400,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:274",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990400,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583102064,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:760",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102064,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583287520,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:759",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287520,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392816,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392816,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732208,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:936",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732208,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852528,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:938",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852528,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877344,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:962",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877344,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242272,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:962",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242272,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849056,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:961",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849056,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585551568,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:959",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551568,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585782352,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:1054",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782352,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586030464,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:1097",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586030464,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495144048,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__arm64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495144048,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228531792,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228531792,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289063328,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289063328,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274393080,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274393080,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361552,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361552,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298656,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298656,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583345328,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345328,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_capset(struct cred * new, const struct cred * old, const kernel_cap_t * effective, const kernel_cap_t * inheritable, const kernel_cap_t * permitted)
```

```json
{
  "name": "security_capset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440512,
      "name": "security_capset",
      "external": true,
      "loc": "security/security.c:793",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440512,
      "name": "security_capset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
