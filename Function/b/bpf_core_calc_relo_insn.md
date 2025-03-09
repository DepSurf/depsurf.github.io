# Function: <code>bpf_core_calc_relo_insn</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_core_calc_relo_insn(const char * prog_name, const struct bpf_core_relo * relo, int relo_idx, const struct btf * local_btf, struct bpf_core_cand_list * cands, struct bpf_core_spec * specs_scratch, struct bpf_core_relo_res * targ_res)
```

```json
{
  "name": "bpf_core_calc_relo_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_calc_relo_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1169",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593962958,
      "name": "bpf_core_calc_relo_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071581774272,
      "name": "bpf_core_calc_relo_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1552
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
int bpf_core_calc_relo_insn(const char * prog_name, const struct bpf_core_relo * relo, int relo_idx, const struct btf * local_btf, struct bpf_core_cand_list * cands, struct bpf_core_spec * specs_scratch, struct bpf_core_relo_res * targ_res)
```

```json
{
  "name": "bpf_core_calc_relo_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_calc_relo_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1280",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023100,
      "name": "bpf_core_calc_relo_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071582197184,
      "name": "bpf_core_calc_relo_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1587
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
int bpf_core_calc_relo_insn(const char * prog_name, const struct bpf_core_relo * relo, int relo_idx, const struct btf * local_btf, struct bpf_core_cand_list * cands, struct bpf_core_spec * specs_scratch, struct bpf_core_relo_res * targ_res)
```

```json
{
  "name": "bpf_core_calc_relo_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_calc_relo_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1280",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545208,
      "name": "bpf_core_calc_relo_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071582397040,
      "name": "bpf_core_calc_relo_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1587
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
int bpf_core_calc_relo_insn(const char * prog_name, const struct bpf_core_relo * relo, int relo_idx, const struct btf * local_btf, struct bpf_core_cand_list * cands, struct bpf_core_spec * specs_scratch, struct bpf_core_relo_res * targ_res)
```

```json
{
  "name": "bpf_core_calc_relo_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_calc_relo_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1280",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:bpf_core_apply",
        "kernel/bpf/btf.c:bpf_core_apply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597448903,
      "name": "bpf_core_calc_relo_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071582564672,
      "name": "bpf_core_calc_relo_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1587
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int bpf_core_calc_relo_insn(const char * prog_name, const struct bpf_core_relo * relo, int relo_idx, const struct btf * local_btf, struct bpf_core_cand_list * cands, struct bpf_core_spec * specs_scratch, struct bpf_core_relo_res * targ_res)
```
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
