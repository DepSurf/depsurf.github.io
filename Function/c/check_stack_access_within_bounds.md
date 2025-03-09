# Function: <code>check_stack_access_within_bounds</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum stack_access_src src, enum bpf_access_type type)
```

```json
{
  "name": "check_stack_access_within_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969264,
      "name": "check_stack_access_within_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3973",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969264,
      "name": "check_stack_access_within_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum stack_access_src src, enum bpf_access_type type)
```

```json
{
  "name": "check_stack_access_within_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178704,
      "name": "check_stack_access_within_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4074",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178704,
      "name": "check_stack_access_within_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type)
```

```json
{
  "name": "check_stack_access_within_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457440,
      "name": "check_stack_access_within_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4623",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457440,
      "name": "check_stack_access_within_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type)
```

```json
{
  "name": "check_stack_access_within_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819664,
      "name": "check_stack_access_within_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5129",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819664,
      "name": "check_stack_access_within_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type)
```

```json
{
  "name": "check_stack_access_within_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953472,
      "name": "check_stack_access_within_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6209",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953472,
      "name": "check_stack_access_within_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type)
```

```json
{
  "name": "check_stack_access_within_bounds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_access_within_bounds",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6584",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_range_initialized",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087216,
      "name": "check_stack_access_within_bounds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
    },
    {
      "addr": 18446744071597435407,
      "name": "check_stack_access_within_bounds.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env * env, int regno, int off, int access_size, enum stack_access_src src, enum bpf_access_type type)
```
</details>
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
<code>enum stack_access_src src</code> ➡️ <code>enum bpf_access_src src</code>
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
