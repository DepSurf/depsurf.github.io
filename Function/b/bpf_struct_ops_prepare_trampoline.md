# Function: <code>bpf_struct_ops_prepare_trampoline</code>

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
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links * tlinks, struct bpf_tramp_link * link, const struct btf_func_model * model, void * image, void * image_end)
```

```json
{
  "name": "bpf_struct_ops_prepare_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756737,
      "name": "bpf_struct_ops_prepare_trampoline",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:335",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ],
      "caller_func": [
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758608,
      "name": "bpf_struct_ops_prepare_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links * tlinks, struct bpf_tramp_link * link, const struct btf_func_model * model, void * image, void * image_end)
```

```json
{
  "name": "bpf_struct_ops_prepare_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582172576,
      "name": "bpf_struct_ops_prepare_trampoline",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:335",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ],
      "caller_func": [
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174800,
      "name": "bpf_struct_ops_prepare_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links * tlinks, struct bpf_tramp_link * link, const struct btf_func_model * model, void * image, void * image_end)
```

```json
{
  "name": "bpf_struct_ops_prepare_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582370656,
      "name": "bpf_struct_ops_prepare_trampoline",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:352",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ],
      "caller_func": [
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372512,
      "name": "bpf_struct_ops_prepare_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links * tlinks, struct bpf_tramp_link * link, const struct btf_func_model * model, void * stub_func, void * image, void * image_end)
```

```json
{
  "name": "bpf_struct_ops_prepare_trampoline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582538160,
      "name": "bpf_struct_ops_prepare_trampoline",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:352",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582538160,
      "name": "bpf_struct_ops_prepare_trampoline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links * tlinks, struct bpf_tramp_link * link, const struct btf_func_model * model, void * image, void * image_end)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * stub_func</code>
</li>
<li>
<b>Param reordered. </b>
<code>tlinks, link, model, image, image_end</code> ➡️ <code>tlinks, link, model, stub_func, image, image_end</code>
</li>
</ul>
</details>
</li>
</ul>
