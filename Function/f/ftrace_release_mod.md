# Function: <code>ftrace_release_mod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175776,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:4901",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/trace/ftrace.c:ftrace_module_notify_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175776,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210432,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:4951",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210432,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580251200,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5000",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251200,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263856,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5695",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263856,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315824,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5734",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:SyS_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315824,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376528,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5720",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376528,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432912,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5680",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432912,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5728",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580492673,
      "name": "ftrace_release_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580485536,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534672,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534672,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625264,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6256",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625264,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615648,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6394",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615648,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580617968,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6399",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617968,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6400",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167253,
      "name": "ftrace_release_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580789616,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6822",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593940791,
      "name": "ftrace_release_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071581010592,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6938",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003117,
      "name": "ftrace_release_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071581310768,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6753",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521665,
      "name": "ftrace_release_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071581405744,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6757",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422113,
      "name": "ftrace_release_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071581513392,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491816344,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__arm64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491816344,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225764608,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__se_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225764608,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284878848,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__se_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284878848,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272126630,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__se_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272126630,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580503472,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503472,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450496,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450496,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494720,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494720,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void ftrace_release_mod(struct module * mod)
```

```json
{
  "name": "ftrace_release_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580550928,
      "name": "ftrace_release_mod",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5765",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580550928,
      "name": "ftrace_release_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
