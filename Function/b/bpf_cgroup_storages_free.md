# Function: <code>bpf_cgroup_storages_free</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581130148,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:31",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122656,
      "name": "bpf_cgroup_storages_free",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581163720,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:31",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156336,
      "name": "bpf_cgroup_storages_free",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581180684,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:31",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172272,
      "name": "bpf_cgroup_storages_free",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581420542,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:31",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411376,
      "name": "bpf_cgroup_storages_free",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581747282,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:70",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736048,
      "name": "bpf_cgroup_storages_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159008,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147520,
      "name": "bpf_cgroup_storages_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582356542,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344976,
      "name": "bpf_cgroup_storages_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```

```json
{
  "name": "bpf_cgroup_storages_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582523373,
      "name": "bpf_cgroup_storages_free",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511680,
      "name": "bpf_cgroup_storages_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void bpf_cgroup_storages_free(struct bpf_cgroup_storage * * storages)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
