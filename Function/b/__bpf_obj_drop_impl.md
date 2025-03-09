# Function: <code>__bpf_obj_drop_impl</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __bpf_obj_drop_impl(void * p, const struct btf_record * rec)
```

```json
{
  "name": "__bpf_obj_drop_impl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125296,
      "name": "__bpf_obj_drop_impl",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1904",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/helpers.c:bpf_rbtree_add_impl",
        "kernel/bpf/helpers.c:bpf_list_push_back_impl",
        "kernel/bpf/helpers.c:bpf_list_push_front_impl",
        "kernel/bpf/helpers.c:bpf_obj_drop_impl",
        "kernel/bpf/helpers.c:bpf_rb_root_free",
        "kernel/bpf/helpers.c:bpf_list_head_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125296,
      "name": "__bpf_obj_drop_impl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_obj_drop_impl(void * p, const struct btf_record * rec, bool percpu)
```

```json
{
  "name": "__bpf_obj_drop_impl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582266534,
      "name": "__bpf_obj_drop_impl",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1927",
      "file": "kernel/bpf/helpers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_obj_drop_impl"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/helpers.c:bpf_rbtree_add_impl",
        "kernel/bpf/helpers.c:bpf_list_push_back_impl",
        "kernel/bpf/helpers.c:bpf_list_push_front_impl",
        "kernel/bpf/helpers.c:bpf_rb_root_free",
        "kernel/bpf/helpers.c:bpf_list_head_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265936,
      "name": "__bpf_obj_drop_impl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void __bpf_obj_drop_impl(void * p, const struct btf_record * rec)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool percpu</code>
</li>
</ul>
</details>
</li>
</ul>
