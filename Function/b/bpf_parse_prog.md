# Function: <code>bpf_parse_prog</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587076976,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:204",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587076976,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587205536,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:204",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205536,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719856,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:204",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719856,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588053616,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:204",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053616,
      "name": "bpf_parse_prog.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588221920,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:203",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221920,
      "name": "bpf_parse_prog.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588556032,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:330",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556032,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588773040,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773040,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644528,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644528,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589668208,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668208,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589559360,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559360,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590304336,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590304336,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591889184,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591889184,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593691456,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593691456,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594172256,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:332",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594172256,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594968800,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:332",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594968800,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502338776,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502338776,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```

```json
{
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235079468,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235079468,
      "name": "bpf_parse_prog",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295861872,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295861872,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278561306,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278561306,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588379424,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379424,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588092112,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588092112,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588711600,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711600,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
  "name": "bpf_parse_prog",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588851856,
      "name": "bpf_parse_prog",
      "external": false,
      "loc": "net/core/lwt_bpf.c:333",
      "file": "net/core/lwt_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state",
        "net/core/lwt_bpf.c:bpf_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851856,
      "name": "bpf_parse_prog.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int bpf_parse_prog(struct nlattr * attr, struct bpf_lwt_prog * prog, enum bpf_prog_type type)
```
</details>
</li>
</ul>
