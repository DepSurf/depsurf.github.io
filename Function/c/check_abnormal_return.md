# Function: <code>check_abnormal_return</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8279",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9457",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int check_abnormal_return(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9783",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183392,
      "name": "check_abnormal_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071592181438,
      "name": "check_abnormal_return.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int check_abnormal_return(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10765",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581468096,
      "name": "check_abnormal_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071593956172,
      "name": "check_abnormal_return.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int check_abnormal_return(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12737",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827872,
      "name": "check_abnormal_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071596015889,
      "name": "check_abnormal_return.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int check_abnormal_return(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14716",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960416,
      "name": "check_abnormal_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071596534277,
      "name": "check_abnormal_return.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_abnormal_return",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_abnormal_return",
      "external": false,
      "loc": "kernel/bpf/verifier.c:15696",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int check_abnormal_return(struct bpf_verifier_env * env)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int check_abnormal_return(struct bpf_verifier_env * env)
```
</details>
</li>
</ul>
