# Function: <code>bpf_fentry_test5</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589849328,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:140",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589849328,
      "name": "bpf_fentry_test5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589888080,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:141",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589888080,
      "name": "bpf_fentry_test5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589794368,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:188",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589794368,
      "name": "bpf_fentry_test5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590553952,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:189",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590553952,
      "name": "bpf_fentry_test5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592167520,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:509",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592167520,
      "name": "bpf_fentry_test5",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593995040,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:508",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593995040,
      "name": "bpf_fentry_test5",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594372224,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:529",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594372224,
      "name": "bpf_fentry_test5",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
```

```json
{
  "name": "bpf_fentry_test5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595173040,
      "name": "bpf_fentry_test5",
      "external": true,
      "loc": "net/bpf/test_run.c:529",
      "file": "net/bpf/test_run.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/bpf/test_run.c:bpf_prog_test_run_tracing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595173040,
      "name": "bpf_fentry_test5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_fentry_test5(u64 a, void * b, short int c, int d, u64 e)
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
