# Function: <code>check_map_access_type</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798192,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2128",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798192,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849296,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849296,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977664,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2458",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977664,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980560,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2531",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980560,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967040,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3072",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967040,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175616,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3138",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175616,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455776,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3501",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455776,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817872,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3943",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817872,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951760,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4828",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951760,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078800,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4986",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078800,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492174216,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492174216,
      "name": "check_map_access_type",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226071396,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226071396,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285387792,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285387792,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272330254,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272330254,
      "name": "check_map_access_type",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580818096,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818096,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764272,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764272,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809344,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809344,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
```

```json
{
  "name": "check_map_access_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580867728,
      "name": "check_map_access_type",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867728,
      "name": "check_map_access_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int check_map_access_type(struct bpf_verifier_env * env, u32 regno, int off, int size, enum bpf_access_type type)
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
