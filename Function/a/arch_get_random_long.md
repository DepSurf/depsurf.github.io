# Function: <code>arch_get_random_long</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594996510,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:101",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584162489,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:101",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:init_std_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595159988,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584506949,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_long",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595402563,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584689061,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_long",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596322025,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584778357,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602639979,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585198464,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602809636,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433685,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604604678,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585559285,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:100",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:init_std_data",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604700273,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777733,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": [
        "drivers/char/random.c:init_std_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585765792,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604712657,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585920437,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": [
        "drivers/char/random.c:init_std_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908144,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579087807,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586649588,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646320,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591246715,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591378753,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/random32.c:prandom_init_early",
        "lib/random32.c:prandom_init_early"
      ]
    },
    {
      "addr": 18446744071586760196,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378753,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586757024,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614262548,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591320988,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/random32.c:prandom_init_early",
        "lib/random32.c:prandom_init_early"
      ]
    },
    {
      "addr": 18446744071586643229,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": [
        "drivers/char/random.c:rand_initialize",
        "drivers/char/random.c:rand_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320988,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586638768,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615183832,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592322864,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "lib/random32.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/random32.c:prandom_init_early",
        "lib/random32.c:prandom_init_early"
      ]
    },
    {
      "addr": 18446744071587190493,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:do_numa_crng_init",
        "drivers/char/random.c:do_numa_crng_init"
      ],
      "caller_func": [
        "drivers/char/random.c:rand_initialize",
        "drivers/char/random.c:rand_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592322864,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587185536,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616950137,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588493888,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:73",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588493888,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "include/linux/random.h:170",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "include/linux/random.h:170",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/powerpc/include/asm/archrandom.h:9",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "include/linux/random.h:170",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604638947,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585681413,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": [
        "drivers/char/random.c:init_std_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669136,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604606884,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585541285,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": [
        "drivers/char/random.c:init_std_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585529488,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604716739,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585870837,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": [
        "drivers/char/random.c:init_std_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858544,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```

```json
{
  "name": "arch_get_random_long",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604716769,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585978741,
      "name": "arch_get_random_long",
      "external": false,
      "loc": "arch/x86/include/asm/archrandom.h:87",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_u64",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:extract_buf",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_reseed",
        "drivers/char/random.c:crng_initialize",
        "drivers/char/random.c:crng_initialize"
      ],
      "caller_func": [
        "drivers/char/random.c:init_std_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966912,
      "name": "arch_get_random_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool arch_get_random_long(long unsigned int * v)
```
</details>
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
