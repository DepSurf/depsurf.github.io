# Function: <code>__module_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579920272,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4021",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:is_module_address",
        "kernel/jump_label.c:jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920272,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579950928,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4192",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:module_address_lookup",
        "kernel/jump_label.c:jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950928,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579982128,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4213",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:module_address_lookup",
        "kernel/jump_label.c:jump_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982128,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985536,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4259",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985536,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032128,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4297",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032128,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580088176,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4334",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088176,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580136000,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4372",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136000,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580182656,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4400",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182656,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230752,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230752,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580295440,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4475",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:is_module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295440,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580303536,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4707",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:is_module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303536,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307072,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4646",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:is_module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307072,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580460885,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4669",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:is_module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup"
      ],
      "caller_func": [
        "kernel/module.c:is_module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436096,
      "name": "__module_address.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071580460832,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580484033,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module/main.c:3049",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:is_module_address"
      ],
      "caller_func": [
        "kernel/module/main.c:__module_text_address",
        "kernel/module/main.c:search_module_extables",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484176,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580734737,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module/main.c:3059",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:is_module_address"
      ],
      "caller_func": [
        "arch/x86/kernel/callthunks.c:is_coretext",
        "kernel/module/main.c:__module_text_address",
        "kernel/module/main.c:search_module_extables",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734896,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814816,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module/main.c:3262",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/callthunks.c:is_coretext",
        "kernel/module/main.c:is_module_text_address",
        "kernel/module/main.c:is_module_address",
        "kernel/module/main.c:search_module_extables",
        "kernel/module/main.c:symbol_put_addr",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:get_modules_for_addrs",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814816,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904208,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module/main.c:3273",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/callthunks.c:is_coretext",
        "kernel/module/main.c:is_module_text_address",
        "kernel/module/main.c:is_module_address",
        "kernel/module/main.c:search_module_extables",
        "kernel/module/main.c:symbol_put_addr",
        "kernel/module/kallsyms.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:get_modules_for_addrs",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_update",
        "kernel/jump_label.c:jump_label_add_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904208,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491470888,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491470888,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225454552,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225454552,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284449360,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:is_module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/module.c:symbol_put_addr"
      ],
      "caller_func": [
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284422960,
      "name": "__module_address.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 13835058055284423312,
      "name": "__module_address",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271922048,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271922048,
      "name": "__module_address",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580199552,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199552,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146992,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146992,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580191024,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191024,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct module * __module_address(long unsigned int addr)
```

```json
{
  "name": "__module_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243360,
      "name": "__module_address",
      "external": true,
      "loc": "kernel/module.c:4467",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__module_text_address",
        "kernel/module.c:is_module_address",
        "kernel/module.c:search_module_extables",
        "kernel/module.c:module_address_lookup",
        "kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint",
        "kernel/jump_label.c:jump_label_module_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243360,
      "name": "__module_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
