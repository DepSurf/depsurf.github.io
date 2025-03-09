# Function: <code>__bpf_selem_unlink_storage</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "__bpf_selem_unlink_storage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137616,
      "name": "__bpf_selem_unlink_storage",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:139",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137616,
      "name": "__bpf_selem_unlink_storage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "__bpf_selem_unlink_storage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094000,
      "name": "__bpf_selem_unlink_storage",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:139",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094000,
      "name": "__bpf_selem_unlink_storage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "__bpf_selem_unlink_storage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323248,
      "name": "__bpf_selem_unlink_storage",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:139",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323248,
      "name": "__bpf_selem_unlink_storage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem, bool use_trace_rcu)
```

```json
{
  "name": "__bpf_selem_unlink_storage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626576,
      "name": "__bpf_selem_unlink_storage",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:161",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626576,
      "name": "__bpf_selem_unlink_storage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem, bool use_trace_rcu)
```

```json
{
  "name": "__bpf_selem_unlink_storage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012816,
      "name": "__bpf_selem_unlink_storage",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:170",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012816,
      "name": "__bpf_selem_unlink_storage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __bpf_selem_unlink_storage(struct bpf_local_storage_elem * selem, bool use_trace_rcu)
```
</details>
</li>
</ul>
