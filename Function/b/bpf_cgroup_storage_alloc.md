# Function: <code>bpf_cgroup_storage_alloc</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780000,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:457",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780000,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864656,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864656,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915680,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915680,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062752,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062752,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074608,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:486",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074608,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089600,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:487",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089600,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318720,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:493",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318720,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620592,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:493",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620592,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005504,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:492",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005504,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196528,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:499",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196528,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582345440,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:499",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345440,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492249496,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492249496,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226142120,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226142120,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285478080,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285478080,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272391914,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272391914,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884480,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884480,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830544,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830544,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875728,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875728,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```

```json
{
  "name": "bpf_cgroup_storage_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934368,
      "name": "bpf_cgroup_storage_alloc",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:477",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934368,
      "name": "bpf_cgroup_storage_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct bpf_cgroup_storage * bpf_cgroup_storage_alloc(struct bpf_prog * prog, enum bpf_cgroup_storage_type stype)
```
</details>
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
