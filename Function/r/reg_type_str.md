# Function: <code>reg_type_str</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * reg_type_str(struct bpf_verifier_env * env, enum bpf_reg_type type)
```

```json
{
  "name": "reg_type_str",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581546015,
      "name": "reg_type_str",
      "external": false,
      "loc": "kernel/bpf/verifier.c:533",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:mark_reg_read",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436448,
      "name": "reg_type_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
const char * reg_type_str(struct bpf_verifier_env * env, enum bpf_reg_type type)
```

```json
{
  "name": "reg_type_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790256,
      "name": "reg_type_str",
      "external": false,
      "loc": "kernel/bpf/verifier.c:570",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:mark_reg_read",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790256,
      "name": "reg_type_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
const char * reg_type_str(struct bpf_verifier_env * env, enum bpf_reg_type type)
```

```json
{
  "name": "reg_type_str",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954064,
      "name": "reg_type_str",
      "external": false,
      "loc": "kernel/bpf/verifier.c:594",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:mark_reg_read",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state",
        "kernel/bpf/verifier.c:print_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954064,
      "name": "reg_type_str",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
const char * reg_type_str(struct bpf_verifier_env * env, enum bpf_reg_type type)
```

```json
{
  "name": "reg_type_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275984,
      "name": "reg_type_str",
      "external": true,
      "loc": "kernel/bpf/log.c:398",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:check_return_code",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:adjust_ptr_min_max_vals",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_reg_sane_offset",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_kfunc_args",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_reg_type",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_helper_mem_access",
        "kernel/bpf/verifier.c:check_atomic",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:map_kptr_match_type",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:__check_ptr_off_reg",
        "kernel/bpf/verifier.c:mark_reg_read",
        "kernel/bpf/log.c:print_reg_state",
        "kernel/bpf/log.c:print_reg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275984,
      "name": "reg_type_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
const char * reg_type_str(struct bpf_verifier_env * env, enum bpf_reg_type type)
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
