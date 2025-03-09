# Function: <code>bpf_get_kallsym</code>

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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480464,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:462",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter",
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480464,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538944,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:471",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter",
        "kernel/kallsyms.c:update_iter",
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538944,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622816,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:550",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter",
        "kernel/kallsyms.c:update_iter",
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622816,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682384,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:673",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682384,
      "name": "bpf_get_kallsym",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750800,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750800,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801360,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801360,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918656,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:738",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918656,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914656,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:734",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914656,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918384,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:740",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918384,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581120832,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:741",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120832,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389856,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:744",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389856,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738448,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:752",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738448,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897872,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:753",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897872,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582021760,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:796",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582021760,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492115552,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492115552,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226017124,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226017124,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285322848,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285322848,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272288248,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272288248,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770160,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770160,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716336,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716336,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761408,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761408,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "bpf_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819536,
      "name": "bpf_get_kallsym",
      "external": true,
      "loc": "kernel/bpf/core.c:715",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819536,
      "name": "bpf_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
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
