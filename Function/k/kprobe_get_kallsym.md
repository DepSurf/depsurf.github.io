# Function: <code>kprobe_get_kallsym</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504800,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2287",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504800,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580508912,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2292",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580508912,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580676736,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2286",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580676736,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886672,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2504",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886672,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176800,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2511",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176800,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271024,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2524",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271024,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```

```json
{
  "name": "kprobe_get_kallsym",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581377088,
      "name": "kprobe_get_kallsym",
      "external": true,
      "loc": "kernel/kprobes.c:2509",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:update_iter_mod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581377088,
      "name": "kprobe_get_kallsym",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int * value, char * type, char * sym)
```
</details>
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
