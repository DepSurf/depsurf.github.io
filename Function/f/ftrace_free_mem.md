# Function: <code>ftrace_free_mem</code>

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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317712,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6091",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317712,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378384,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6077",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378384,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 801
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434768,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6037",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434768,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580487408,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6085",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487408,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536560,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536560,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6611",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633471,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580626688,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6764",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591318605,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580617312,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6769",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591260753,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580619792,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6770",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167330,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071580791456,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 870
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7204",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593940882,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071581012736,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 887
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7320",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596003148,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581313136,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7135",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596521696,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581408528,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:7137",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597422144,
      "name": "ftrace_free_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071581516192,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491818392,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491818392,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225766664,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225766664,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284881744,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284881744,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272128450,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272128450,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505360,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505360,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452384,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452384,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496608,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496608,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
```

```json
{
  "name": "ftrace_free_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580552880,
      "name": "ftrace_free_mem",
      "external": true,
      "loc": "kernel/trace/ftrace.c:6118",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:do_init_module",
        "kernel/trace/ftrace.c:ftrace_free_init_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552880,
      "name": "ftrace_free_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
void ftrace_free_mem(struct module * mod, void * start_ptr, void * end_ptr)
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
