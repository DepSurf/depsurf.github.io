# Function: <code>bpf_core_patch_insn</code>

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
int bpf_core_patch_insn(const char * prog_name, struct bpf_insn * insn, int insn_idx, const struct bpf_core_relo * relo, int relo_idx, const struct bpf_core_relo_res * res)
```

```json
{
  "name": "bpf_core_patch_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_patch_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:928",
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
      "addr": 18446744071593962742,
      "name": "bpf_core_patch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071581772224,
      "name": "bpf_core_patch_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1138
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
int bpf_core_patch_insn(const char * prog_name, struct bpf_insn * insn, int insn_idx, const struct bpf_core_relo * relo, int relo_idx, const struct bpf_core_relo_res * res)
```

```json
{
  "name": "bpf_core_patch_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_patch_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1024",
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
      "addr": 18446744071596022884,
      "name": "bpf_core_patch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071582195024,
      "name": "bpf_core_patch_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int bpf_core_patch_insn(const char * prog_name, struct bpf_insn * insn, int insn_idx, const struct bpf_core_relo * relo, int relo_idx, const struct bpf_core_relo_res * res)
```

```json
{
  "name": "bpf_core_patch_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_patch_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1024",
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
      "addr": 18446744071596544992,
      "name": "bpf_core_patch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071582394864,
      "name": "bpf_core_patch_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
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
int bpf_core_patch_insn(const char * prog_name, struct bpf_insn * insn, int insn_idx, const struct bpf_core_relo * relo, int relo_idx, const struct bpf_core_relo_res * res)
```

```json
{
  "name": "bpf_core_patch_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_core_patch_insn",
      "external": true,
      "loc": "tools/lib/bpf/relo_core.c:1024",
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
      "addr": 18446744071597448687,
      "name": "bpf_core_patch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071582562496,
      "name": "bpf_core_patch_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1137
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
int bpf_core_patch_insn(const char * prog_name, struct bpf_insn * insn, int insn_idx, const struct bpf_core_relo * relo, int relo_idx, const struct bpf_core_relo_res * res)
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
