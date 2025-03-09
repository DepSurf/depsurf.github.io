# Function: <code>prctl_set_seccomp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int prctl_set_seccomp(long unsigned int seccomp_mode, char * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139568,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:845",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139568,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, char * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173648,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:810",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173648,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, char * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580214256,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:809",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214256,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, char * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224192,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:929",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224192,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, char * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275392,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:953",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275392,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, char * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336416,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:959",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336416,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580392256,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1403",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580392256,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444976,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1418",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444976,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494000,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494000,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580579568,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1462",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580579568,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569248,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1953",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569248,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572416,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:2001",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572416,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742272,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1983",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742272,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955632,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:2020",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955632,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581250256,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:2020",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250256,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345264,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:2020",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345264,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581452336,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:2084",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581452336,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491770424,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491770424,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225719000,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225719000,
      "name": "prctl_set_seccomp",
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284815552,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284815552,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272089230,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272089230,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462800,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462800,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409840,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409840,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580454048,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454048,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
long int prctl_set_seccomp(long unsigned int seccomp_mode, void * filter)
```

```json
{
  "name": "prctl_set_seccomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580509712,
      "name": "prctl_set_seccomp",
      "external": true,
      "loc": "kernel/seccomp.c:1441",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509712,
      "name": "prctl_set_seccomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * filter</code> ➡️ <code>void * filter</code>
</li>
</ul>
</details>
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
