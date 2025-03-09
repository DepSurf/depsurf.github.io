# Function: <code>bpf_convert_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_insn * new_prog, int * new_len)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385760,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:358",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385760,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2493
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_insn * new_prog, int * new_len)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822976,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:359",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822976,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2373
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_insn * new_prog, int * new_len)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010512,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:361",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010512,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2373
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587137280,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:370",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137280,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2407
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587642000,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:372",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587642000,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:534",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982864,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3437
    },
    {
      "addr": 18446744071587989433,
      "name": "bpf_convert_filter.cold.96",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139968,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4154
    },
    {
      "addr": 18446744071588148241,
      "name": "bpf_convert_filter.cold.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460752,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2847
    },
    {
      "addr": 18446744071588469334,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666384,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2783
    },
    {
      "addr": 18446744071588674779,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:525",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:bpf_migrate_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589497520,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2786
    },
    {
      "addr": 18446744071589540349,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:555",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:bpf_migrate_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499856,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2786
    },
    {
      "addr": 18446744071591630665,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:555",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398208,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2669
    },
    {
      "addr": 18446744071591574098,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:556",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590134816,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2688
    },
    {
      "addr": 18446744071592701895,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:557",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591688528,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2792
    },
    {
      "addr": 18446744071594588427,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:559",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593477600,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2805
    },
    {
      "addr": 18446744071596326910,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:559",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593943072,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2731
    },
    {
      "addr": 18446744071596857165,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:564",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594725840,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2731
    },
    {
      "addr": 18446744071597782170,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502208984,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502208984,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1988
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234963616,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234963616,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2860
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295703424,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295703424,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3360
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
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278464972,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278464972,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588273120,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2783
    },
    {
      "addr": 18446744071588281515,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587985936,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2783
    },
    {
      "addr": 18446744071587994331,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588604944,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2783
    },
    {
      "addr": 18446744071588613339,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int bpf_convert_filter(struct sock_filter * prog, int len, struct bpf_prog * new_prog, int * new_len, bool * seen_ld_abs)
```

```json
{
  "name": "bpf_convert_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_convert_filter",
      "external": false,
      "loc": "net/core/filter.c:536",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742624,
      "name": "bpf_convert_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2783
    },
    {
      "addr": 18446744071588751019,
      "name": "bpf_convert_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_insn * new_prog</code> ➡️ <code>struct bpf_prog * new_prog</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * seen_ld_abs</code>
</li>
</ul>
</details>
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
