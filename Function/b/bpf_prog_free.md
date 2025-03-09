# Function: <code>bpf_prog_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356832,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:726",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__prog_put_common",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:__bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356832,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411808,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1004",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "net/core/filter.c:__bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411808,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459952,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1086",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "net/core/filter.c:__bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459952,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470976,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1333",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470976,
      "name": "bpf_prog_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527088,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1578",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527088,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580616128,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1745",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616128,
      "name": "bpf_prog_free",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580675136,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1997",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675136,
      "name": "bpf_prog_free",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580740480,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580740480,
      "name": "bpf_prog_free",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791200,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791200,
      "name": "bpf_prog_free",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913296,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913296,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909264,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2148",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909264,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912816,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2273",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912816,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115200,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2293",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115200,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384192,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2581",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384192,
      "name": "bpf_prog_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732816,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2579",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732816,
      "name": "bpf_prog_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891904,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2596",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891904,
      "name": "bpf_prog_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015536,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:2776",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_noref",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015536,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492104632,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492104632,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226005820,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226005820,
      "name": "bpf_prog_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285307824,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285307824,
      "name": "bpf_prog_free",
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272279608,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272279608,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760000,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760000,
      "name": "bpf_prog_free",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706176,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706176,
      "name": "bpf_prog_free",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751248,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751248,
      "name": "bpf_prog_free",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809344,
      "name": "bpf_prog_free",
      "external": true,
      "loc": "kernel/bpf/core.c:1990",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:__bpf_prog_put_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809344,
      "name": "bpf_prog_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
