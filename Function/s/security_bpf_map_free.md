# Function: <code>security_bpf_map_free</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807456,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2469",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807456,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001584,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:1782",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001584,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114912,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2542",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114912,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301792,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2559",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301792,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406304,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406304,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746544,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2969",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746544,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866864,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2987",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866864,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583893024,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:3050",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893024,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256848,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:3058",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256848,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868816,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:3136",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868816,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585574048,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:3116",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574048,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805312,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:5563",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805312,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586053760,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:5704",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053760,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495160080,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495160080,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228547444,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228547444,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289095024,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289095024,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274405116,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274405116,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375040,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375040,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312144,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312144,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358816,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358816,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void security_bpf_map_free(struct bpf_map * map)
```

```json
{
  "name": "security_bpf_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583454000,
      "name": "security_bpf_map_free",
      "external": true,
      "loc": "security/security.c:2598",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454000,
      "name": "security_bpf_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void security_bpf_map_free(struct bpf_map * map)
```
</details>
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
