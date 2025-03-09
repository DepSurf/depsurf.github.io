# Function: <code>tnum_add</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580588245,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:46",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587968,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580683699,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:56",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683456,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580754611,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:56",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_reg_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754368,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838417,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:57",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838176,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580889457,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889216,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029354,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029104,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036682,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036432,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050071,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049824,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581274821,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274576,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568341,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568032,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581944325,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943936,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582129813,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129424,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582271397,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271008,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492216008,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492215536,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226113544,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226112812,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285437108,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285436864,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272364016,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272363586,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580858257,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858016,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580804385,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804144,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580849505,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849264,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
```

```json
{
  "name": "tnum_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580907825,
      "name": "tnum_add",
      "external": true,
      "loc": "kernel/bpf/tnum.c:62",
      "file": "kernel/bpf/tnum.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/tnum.c:tnum_mul",
        "kernel/bpf/tnum.c:tnum_mul"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:adjust_scalar_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_ptr_alignment",
        "kernel/bpf/verifier.c:check_ptr_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907584,
      "name": "tnum_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct tnum tnum_add(struct tnum a, struct tnum b)
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
