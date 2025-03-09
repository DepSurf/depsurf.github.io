# Function: <code>module_arch_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241680,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:253",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241680,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241200,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:254",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241200,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253648,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:254",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253648,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579249360,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:254",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249360,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266144,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:277",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266144,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579277264,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:277",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277264,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579301248,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:283",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301248,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317856,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:271",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317856,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321888,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:271",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321888,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579351136,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:299",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351136,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350976,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:300",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350976,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579355616,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:300",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355616,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413248,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:304",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413248,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480512,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:323",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480512,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579573664,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:356",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573664,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579586224,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:379",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586224,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579615984,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:369",
      "file": "arch/x86/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615984,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491479256,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "kernel/module.c:2181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491479256,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224439968,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/arm/kernel/module.c:407",
      "file": "arch/arm/kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224439968,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284430512,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "kernel/module.c:2181",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284430512,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 12
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271925370,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "kernel/module.c:2181",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271925370,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317792,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:271",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317792,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252384,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:271",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252384,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317712,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:271",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317712,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void module_arch_cleanup(struct module * mod)
```

```json
{
  "name": "module_arch_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326000,
      "name": "module_arch_cleanup",
      "external": true,
      "loc": "arch/x86/kernel/module.c:271",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:free_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326000,
      "name": "module_arch_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
