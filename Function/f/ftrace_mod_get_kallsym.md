# Function: <code>ftrace_mod_get_kallsym</code>

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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317520,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5987",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:get_ksymbol_ftrace_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317520,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378192,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5973",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:get_ksymbol_ftrace_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378192,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434576,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5933",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434576,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:5981",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580492704,
      "name": "ftrace_mod_get_kallsym.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580487216,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536368,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536368,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626496,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6511",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626496,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6649",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591318581,
      "name": "ftrace_mod_get_kallsym.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580616896,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6654",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260729,
      "name": "ftrace_mod_get_kallsym.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580619360,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6655",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167306,
      "name": "ftrace_mod_get_kallsym.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580791024,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7089",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593940858,
      "name": "ftrace_mod_get_kallsym.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581012224,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312592,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7205",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312592,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408048,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7020",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408048,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515712,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7022",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515712,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491818136,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491818136,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225766428,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225766428,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284881408,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284881408,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272128252,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272128252,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505168,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505168,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452192,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452192,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496416,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496416,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
```

```json
{
  "name": "ftrace_mod_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580552656,
      "name": "ftrace_mod_get_kallsym",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6018",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552656,
      "name": "ftrace_mod_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * name, char * module_name, int * exported)
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
