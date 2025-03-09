# Function: <code>check_stack_range_initialized</code>

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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum stack_access_src type, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_range_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970448,
      "name": "check_stack_range_initialized",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4349",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970448,
      "name": "check_stack_range_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum stack_access_src type, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_range_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_range_initialized",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4463",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180272,
      "name": "check_stack_range_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1238
    },
    {
      "addr": 18446744071592181206,
      "name": "check_stack_range_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_range_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_range_initialized",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5041",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459184,
      "name": "check_stack_range_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1269
    },
    {
      "addr": 18446744071593955075,
      "name": "check_stack_range_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_range_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_range_initialized",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5546",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_stack_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821456,
      "name": "check_stack_range_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
    },
    {
      "addr": 18446744071596015419,
      "name": "check_stack_range_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_range_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_range_initialized",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6626",
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
      "addr": 18446744071581962208,
      "name": "check_stack_range_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1730
    },
    {
      "addr": 18446744071596534440,
      "name": "check_stack_range_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta * meta)
```

```json
{
  "name": "check_stack_range_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_stack_range_initialized",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6997",
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
      "addr": 18446744071582092400,
      "name": "check_stack_range_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1549
    },
    {
      "addr": 18446744071597435793,
      "name": "check_stack_range_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int check_stack_range_initialized(struct bpf_verifier_env * env, int regno, int off, int access_size, bool zero_size_allowed, enum stack_access_src type, struct bpf_call_arg_meta * meta)
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
<code>enum stack_access_src type</code> ➡️ <code>enum bpf_access_src type</code>
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
