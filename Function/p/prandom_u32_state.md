# Function: <code>prandom_u32_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583008752,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:59",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:__prandom_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008752,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299200,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:59",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299200,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418240,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:59",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418240,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439280,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:59",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439280,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619248,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619248,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835696,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835696,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583919328,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919328,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099088,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099088,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221872,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221872,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584628506,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627728,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584747818,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584746128,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584776154,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774432,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585206170,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204320,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586041690,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586041168,
      "name": "prandom_u32_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587024273,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023712,
      "name": "prandom_u32_state",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587279265,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587278704,
      "name": "prandom_u32_state",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587568001,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:52",
      "file": "lib/random32.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/random32.c:prandom_bytes_state"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587567440,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496095248,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496095248,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229422316,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229422316,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290338880,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290338880,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275163818,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275163818,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584190608,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190608,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125840,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125840,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174368,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174368,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u32 prandom_u32_state(struct rnd_state * state)
```

```json
{
  "name": "prandom_u32_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584278672,
      "name": "prandom_u32_state",
      "external": true,
      "loc": "lib/random32.c:60",
      "file": "lib/random32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_user_rnd_u32",
        "mm/slab_common.c:cache_random_seq_create",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_warmup",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_bytes_state",
        "lib/random32.c:prandom_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278672,
      "name": "prandom_u32_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
