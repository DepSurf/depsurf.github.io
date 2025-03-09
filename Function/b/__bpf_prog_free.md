# Function: <code>__bpf_prog_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580356752,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:133",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356752,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580414283,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:133",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412352,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580463035,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:143",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460576,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580482269,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:146",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478816,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580540778,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:142",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537296,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624516,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:144",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621088,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580684750,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:232",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680544,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580752120,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748528,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580802680,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799104,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921722,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:253",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916384,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915928,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:247",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912336,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919807,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:252",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915904,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581122331,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:252",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118320,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391506,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:257",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387056,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740753,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:265",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735472,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581900228,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:266",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894832,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582027342,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:270",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018592,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492117528,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492112824,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226018708,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226014380,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285325172,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free",
        "arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285319232,
      "name": "__bpf_prog_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272289690,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272285800,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580771480,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767904,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580717656,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714080,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580762728,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759152,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void __bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "__bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580820872,
      "name": "__bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:254",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_prog_realloc"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_free",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817248,
      "name": "__bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
