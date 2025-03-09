# Function: <code>destroy_if_dynptr_stack_slot</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int destroy_if_dynptr_stack_slot(struct bpf_verifier_env * env, struct bpf_func_state * state, int spi)
```

```json
{
  "name": "destroy_if_dynptr_stack_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_if_dynptr_stack_slot",
      "external": false,
      "loc": "kernel/bpf/verifier.c:871",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824288,
      "name": "destroy_if_dynptr_stack_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071596015717,
      "name": "destroy_if_dynptr_stack_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int destroy_if_dynptr_stack_slot(struct bpf_verifier_env * env, struct bpf_func_state * state, int spi)
```

```json
{
  "name": "destroy_if_dynptr_stack_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_if_dynptr_stack_slot",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1036",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019104,
      "name": "destroy_if_dynptr_stack_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
    },
    {
      "addr": 18446744071596537208,
      "name": "destroy_if_dynptr_stack_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int destroy_if_dynptr_stack_slot(struct bpf_verifier_env * env, struct bpf_func_state * state, int spi)
```

```json
{
  "name": "destroy_if_dynptr_stack_slot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "destroy_if_dynptr_stack_slot",
      "external": false,
      "loc": "kernel/bpf/verifier.c:845",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:check_stack_write_var_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr",
        "kernel/bpf/verifier.c:mark_stack_slots_dynptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146752,
      "name": "destroy_if_dynptr_stack_slot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
    },
    {
      "addr": 18446744071597438654,
      "name": "destroy_if_dynptr_stack_slot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int destroy_if_dynptr_stack_slot(struct bpf_verifier_env * env, struct bpf_func_state * state, int spi)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
