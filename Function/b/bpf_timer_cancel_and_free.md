# Function: <code>bpf_timer_cancel_and_free</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_timer_cancel_and_free(void * val)
```

```json
{
  "name": "bpf_timer_cancel_and_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273056,
      "name": "bpf_timer_cancel_and_free",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1290",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_elem_free_rcu",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_node",
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273056,
      "name": "bpf_timer_cancel_and_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void bpf_timer_cancel_and_free(void * val)
```

```json
{
  "name": "bpf_timer_cancel_and_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581565744,
      "name": "bpf_timer_cancel_and_free",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1349",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_free_timers",
        "kernel/bpf/hashtab.c:htab_map_free_timers",
        "kernel/bpf/hashtab.c:check_and_free_fields",
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581565744,
      "name": "bpf_timer_cancel_and_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_timer_cancel_and_free(void * val)
```

```json
{
  "name": "bpf_timer_cancel_and_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938928,
      "name": "bpf_timer_cancel_and_free",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1334",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/syscall.c:bpf_obj_free_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938928,
      "name": "bpf_timer_cancel_and_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_timer_cancel_and_free(void * val)
```

```json
{
  "name": "bpf_timer_cancel_and_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122880,
      "name": "bpf_timer_cancel_and_free",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1353",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/syscall.c:bpf_obj_free_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122880,
      "name": "bpf_timer_cancel_and_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_timer_cancel_and_free(void * val)
```

```json
{
  "name": "bpf_timer_cancel_and_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263408,
      "name": "bpf_timer_cancel_and_free",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1372",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/syscall.c:bpf_obj_free_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263408,
      "name": "bpf_timer_cancel_and_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void bpf_timer_cancel_and_free(void * val)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
