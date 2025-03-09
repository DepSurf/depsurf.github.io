# Function: <code>btf_prepare_func_args</code>

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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * reg)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096336,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:4471",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096336,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * reg)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123216,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:5395",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123216,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1227
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * regs)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581142960,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:5569",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581142960,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1380
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * regs)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:5622",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592187204,
      "name": "btf_prepare_func_args.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581376240,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1462
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * regs)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:6355",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593961652,
      "name": "btf_prepare_func_args.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071581690960,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1567
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * regs)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:6846",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596022186,
      "name": "btf_prepare_func_args.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582089584,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1585
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * regs)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:6948",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596544096,
      "name": "btf_prepare_func_args.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582286080,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1622
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog)
```

```json
{
  "name": "btf_prepare_func_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_prepare_func_args",
      "external": true,
      "loc": "kernel/bpf/btf.c:6957",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check_common",
        "kernel/bpf/verifier.c:do_check_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597447254,
      "name": "btf_prepare_func_args.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071582442384,
      "name": "btf_prepare_func_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2811
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
int btf_prepare_func_args(struct bpf_verifier_env * env, int subprog, struct bpf_reg_state * reg)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state * regs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state * reg</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state * regs</code>
</li>
</ul>
</details>
</li>
</ul>
