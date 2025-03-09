# Function: <code>bpf_core_names_match</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool bpf_core_names_match(const struct btf * local_btf, size_t local_name_off, const struct btf * targ_btf, size_t targ_name_off)
```

```json
{
  "name": "bpf_core_names_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188176,
      "name": "bpf_core_names_match",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:1422",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188176,
      "name": "bpf_core_names_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
bool bpf_core_names_match(const struct btf * local_btf, size_t local_name_off, const struct btf * targ_btf, size_t targ_name_off)
```

```json
{
  "name": "bpf_core_names_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388016,
      "name": "bpf_core_names_match",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:1422",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388016,
      "name": "bpf_core_names_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
bool bpf_core_names_match(const struct btf * local_btf, size_t local_name_off, const struct btf * targ_btf, size_t targ_name_off)
```

```json
{
  "name": "bpf_core_names_match",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555616,
      "name": "bpf_core_names_match",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:1422",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match",
        "tools/lib/bpf/relo_core.c:__bpf_core_types_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555616,
      "name": "bpf_core_names_match",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
bool bpf_core_names_match(const struct btf * local_btf, size_t local_name_off, const struct btf * targ_btf, size_t targ_name_off)
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
