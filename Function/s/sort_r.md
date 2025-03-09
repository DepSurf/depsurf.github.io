# Function: <code>sort_r</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584220016,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220016,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625952,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:199",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625952,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744352,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:199",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744352,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584772496,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:199",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772496,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202384,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:199",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202384,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038912,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:210",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/syscall.c:map_create",
        "mm/slub.c:slab_debug_trace_open",
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038912,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587021200,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:210",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/btf.c:btf_parse_field_offs",
        "mm/slub.c:slab_debug_trace_open",
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587021200,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587276240,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:210",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/btf.c:btf_parse_fields",
        "mm/slub.c:slab_debug_trace_open",
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276240,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void sort_r(void * base, size_t num, size_t size, cmp_r_func_t cmp_func, swap_r_func_t swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587564976,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:210",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/btf.c:btf_parse_fields",
        "mm/slub.c:slab_debug_trace_open",
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587564976,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510868840,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort",
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496093344,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229420344,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229420344,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290335824,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290335824,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275162358,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275162358,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188752,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188752,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123984,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123984,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172512,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172512,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```

```json
{
  "name": "sort_r",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276816,
      "name": "sort_r",
      "external": true,
      "loc": "lib/sort.c:204",
      "file": "lib/sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sort.c:sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276816,
      "name": "sort_r",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void sort_r(void * base, size_t num, size_t size, int (*)(const void *, const void *, const void *) cmp_func, void (*)(void *, void *, int) swap_func, const void * priv)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(const void *, const void *, const void *) cmp_func</code> ➡️ <code>cmp_r_func_t cmp_func</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*)(void *, void *, int) swap_func</code> ➡️ <code>swap_func_t swap_func</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>swap_func_t swap_func</code> ➡️ <code>swap_r_func_t swap_func</code>
</li>
</ul>
</details>
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
