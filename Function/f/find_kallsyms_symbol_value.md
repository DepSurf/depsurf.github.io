# Function: <code>find_kallsyms_symbol_value</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129584,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4127",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129584,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175072,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4155",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175072,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222912,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222912,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580295936,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4229",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295936,
      "name": "find_kallsyms_symbol_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580279648,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4460",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279648,
      "name": "find_kallsyms_symbol_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580283776,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4364",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283776,
      "name": "find_kallsyms_symbol_value.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432336,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4385",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432336,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580490704,
      "name": "find_kallsyms_symbol_value",
      "external": true,
      "loc": "kernel/module/kallsyms.c:445",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name",
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490704,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742304,
      "name": "find_kallsyms_symbol_value",
      "external": true,
      "loc": "kernel/module/kallsyms.c:445",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name",
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742304,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824848,
      "name": "find_kallsyms_symbol_value",
      "external": true,
      "loc": "kernel/module/kallsyms.c:466",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824848,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914288,
      "name": "find_kallsyms_symbol_value",
      "external": true,
      "loc": "kernel/module/kallsyms.c:466",
      "file": "kernel/module/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914288,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491463536,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491463536,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225447352,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225447352,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284410864,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284410864,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271915446,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271915446,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191712,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191712,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139152,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139152,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183184,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183184,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```

```json
{
  "name": "find_kallsyms_symbol_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235424,
      "name": "find_kallsyms_symbol_value",
      "external": false,
      "loc": "kernel/module.c:4222",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/module.c:module_kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235424,
      "name": "find_kallsyms_symbol_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module * mod, const char * name)
```
</details>
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
