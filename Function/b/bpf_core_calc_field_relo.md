# Function: <code>bpf_core_calc_field_relo</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bpf_core_calc_field_relo(const char * prog_name, const struct bpf_core_relo * relo, const struct bpf_core_spec * spec, __u32 * val, __u32 * field_sz, __u32 * type_id, bool * validate)
```

```json
{
  "name": "bpf_core_calc_field_relo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768816,
      "name": "bpf_core_calc_field_relo",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:583",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768816,
      "name": "bpf_core_calc_field_relo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
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
int bpf_core_calc_field_relo(const char * prog_name, const struct bpf_core_relo * relo, const struct bpf_core_spec * spec, __u64 * val, __u32 * field_sz, __u32 * type_id, bool * validate)
```

```json
{
  "name": "bpf_core_calc_field_relo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191008,
      "name": "bpf_core_calc_field_relo",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:678",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191008,
      "name": "bpf_core_calc_field_relo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1051
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
int bpf_core_calc_field_relo(const char * prog_name, const struct bpf_core_relo * relo, const struct bpf_core_spec * spec, __u64 * val, __u32 * field_sz, __u32 * type_id, bool * validate)
```

```json
{
  "name": "bpf_core_calc_field_relo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390848,
      "name": "bpf_core_calc_field_relo",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:678",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390848,
      "name": "bpf_core_calc_field_relo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int bpf_core_calc_field_relo(const char * prog_name, const struct bpf_core_relo * relo, const struct bpf_core_spec * spec, __u64 * val, __u32 * field_sz, __u32 * type_id, bool * validate)
```

```json
{
  "name": "bpf_core_calc_field_relo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558448,
      "name": "bpf_core_calc_field_relo",
      "external": false,
      "loc": "tools/lib/bpf/relo_core.c:678",
      "file": "tools/lib/bpf/relo_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo",
        "tools/lib/bpf/relo_core.c:bpf_core_calc_relo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558448,
      "name": "bpf_core_calc_field_relo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1086
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
int bpf_core_calc_field_relo(const char * prog_name, const struct bpf_core_relo * relo, const struct bpf_core_spec * spec, __u32 * val, __u32 * field_sz, __u32 * type_id, bool * validate)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__u32 * val</code> ➡️ <code>__u64 * val</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
