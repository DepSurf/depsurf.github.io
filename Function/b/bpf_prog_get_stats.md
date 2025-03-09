# Function: <code>bpf_prog_get_stats</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755232,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1354",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755232,
      "name": "bpf_prog_get_stats.isra.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805888,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805888,
      "name": "bpf_prog_get_stats.isra.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_stats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924320,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1762",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924320,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_stats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920416,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1736",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920416,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_stats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924336,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1739",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924336,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_kstats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126912,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1833",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126912,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_kstats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398368,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2077",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398368,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_kstats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751888,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2111",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751888,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_kstats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911904,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2190",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911904,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_kstats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036752,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2230",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036752,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492120968,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492120968,
      "name": "bpf_prog_get_stats.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_stats * stats)
```

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226021744,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226021744,
      "name": "bpf_prog_get_stats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285329024,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285329024,
      "name": "bpf_prog_get_stats.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272292798,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272292798,
      "name": "bpf_prog_get_stats.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580774688,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774688,
      "name": "bpf_prog_get_stats.isra.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580720864,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720864,
      "name": "bpf_prog_get_stats.isra.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580765936,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765936,
      "name": "bpf_prog_get_stats.isra.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_get_stats",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824096,
      "name": "bpf_prog_get_stats",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1375",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824096,
      "name": "bpf_prog_get_stats.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_stats * stats)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_prog_stats * stats</code> ➡️ <code>struct bpf_prog_kstats * stats</code>
</li>
</ul>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog * prog, struct bpf_prog_stats * stats)
```
</details>
</li>
</ul>
