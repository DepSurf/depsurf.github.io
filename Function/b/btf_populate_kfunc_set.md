# Function: <code>btf_populate_kfunc_set</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_populate_kfunc_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581677548,
      "name": "btf_populate_kfunc_set",
      "external": false,
      "loc": "kernel/bpf/btf.c:7078",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int btf_populate_kfunc_set(struct btf * btf, enum btf_kfunc_hook hook, struct btf_id_set8 * add_set)
```

```json
{
  "name": "btf_populate_kfunc_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_populate_kfunc_set",
      "external": false,
      "loc": "kernel/bpf/btf.c:7469",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039968,
      "name": "btf_populate_kfunc_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071596021810,
      "name": "btf_populate_kfunc_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int btf_populate_kfunc_set(struct btf * btf, enum btf_kfunc_hook hook, const struct btf_kfunc_id_set * kset)
```

```json
{
  "name": "btf_populate_kfunc_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_populate_kfunc_set",
      "external": false,
      "loc": "kernel/bpf/btf.c:7673",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232720,
      "name": "btf_populate_kfunc_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
    },
    {
      "addr": 18446744071596543704,
      "name": "btf_populate_kfunc_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int btf_populate_kfunc_set(struct btf * btf, enum btf_kfunc_hook hook, const struct btf_kfunc_id_set * kset)
```

```json
{
  "name": "btf_populate_kfunc_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "btf_populate_kfunc_set",
      "external": false,
      "loc": "kernel/bpf/btf.c:7737",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:__register_btf_kfunc_id_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388768,
      "name": "btf_populate_kfunc_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
    },
    {
      "addr": 18446744071597446944,
      "name": "btf_populate_kfunc_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int btf_populate_kfunc_set(struct btf * btf, enum btf_kfunc_hook hook, struct btf_id_set8 * add_set)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf_kfunc_id_set * kset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct btf_id_set8 * add_set</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
