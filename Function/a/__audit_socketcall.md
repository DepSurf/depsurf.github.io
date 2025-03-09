# Function: <code>__audit_socketcall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062320,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2167",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062320,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095536,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2171",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095536,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135856,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2179",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135856,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141520,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2188",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141520,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194128,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2211",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:SyS_socketcall",
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194128,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253888,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2218",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253888,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307136,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2203",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307136,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359104,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359104,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407872,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407872,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486400,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2371",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486400,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474656,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2388",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474656,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478608,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2385",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478608,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646048,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2399",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646048,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854544,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2671",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854544,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141968,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2649",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141968,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235056,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2648",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235056,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341008,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2638",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341008,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491673392,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491673392,
      "name": "__audit_socketcall",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225627668,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225627668,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284682512,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284682512,
      "name": "__audit_socketcall",
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272063918,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272063918,
      "name": "__audit_socketcall",
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376672,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376672,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323840,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323840,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367920,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367920,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int __audit_socketcall(int nargs, long unsigned int * args)
```

```json
{
  "name": "__audit_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580423408,
      "name": "__audit_socketcall",
      "external": true,
      "loc": "kernel/auditsc.c:2319",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423408,
      "name": "__audit_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
