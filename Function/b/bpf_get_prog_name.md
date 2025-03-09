# Function: <code>bpf_get_prog_name</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470912,
      "name": "bpf_get_prog_name",
      "external": false,
      "loc": "kernel/bpf/core.c:310",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470912,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526960,
      "name": "bpf_get_prog_name",
      "external": false,
      "loc": "kernel/bpf/core.c:306",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526960,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580616000,
      "name": "bpf_get_prog_name",
      "external": false,
      "loc": "kernel/bpf/core.c:387",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616000,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674912,
      "name": "bpf_get_prog_name",
      "external": false,
      "loc": "kernel/bpf/core.c:498",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674912,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749696,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749696,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800272,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800272,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492114088,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492114088,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226015620,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226015620,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285320960,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285320960,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272287062,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272287062,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769072,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769072,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715248,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715248,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760320,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760320,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```

```json
{
  "name": "bpf_get_prog_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818416,
      "name": "bpf_get_prog_name",
      "external": true,
      "loc": "kernel/bpf/core.c:540",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_kallsym",
        "kernel/bpf/core.c:__bpf_address_lookup",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols",
        "kernel/events/core.c:perf_event_bpf_emit_ksymbols"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818416,
      "name": "bpf_get_prog_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void bpf_get_prog_name(const struct bpf_prog * prog, char * sym)
```
</details>
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
