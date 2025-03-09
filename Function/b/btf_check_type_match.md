# Function: <code>btf_check_type_match</code>

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
int btf_check_type_match(struct bpf_verifier_env * env, struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095376,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:4344",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_attach_btf_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095376,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122064,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5268",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122064,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581142640,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5353",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581142640,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375872,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5406",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375872,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690752,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:5960",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690752,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088880,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:6633",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088880,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285376,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:6735",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285376,
      "name": "btf_check_type_match",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int btf_check_type_match(struct bpf_verifier_log * log, const struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```

```json
{
  "name": "btf_check_type_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442160,
      "name": "btf_check_type_match",
      "external": true,
      "loc": "kernel/bpf/btf.c:6907",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check_attach_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442160,
      "name": "btf_check_type_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int btf_check_type_match(struct bpf_verifier_env * env, struct bpf_prog * prog, struct btf * btf2, const struct btf_type * t2)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_log * log</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_env * env</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct bpf_prog * prog</code> ➡️ <code>const struct bpf_prog * prog</code>
</li>
</ul>
</details>
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
