# Function: <code>mem_dump_obj</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_dump_obj(void * object)
```

```json
{
  "name": "mem_dump_obj",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581477012,
      "name": "mem_dump_obj",
      "external": true,
      "loc": "mm/util.c:988",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267439,
      "name": "mem_dump_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581476960,
      "name": "mem_dump_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_dump_obj(void * object)
```

```json
{
  "name": "mem_dump_obj",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581731092,
      "name": "mem_dump_obj",
      "external": true,
      "loc": "mm/util.c:1019",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592192646,
      "name": "mem_dump_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071581731040,
      "name": "mem_dump_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mem_dump_obj(void * object)
```

```json
{
  "name": "mem_dump_obj",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582110999,
      "name": "mem_dump_obj",
      "external": true,
      "loc": "mm/util.c:1144",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593968548,
      "name": "mem_dump_obj.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582110928,
      "name": "mem_dump_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void mem_dump_obj(void * object)
```

```json
{
  "name": "mem_dump_obj",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582585136,
      "name": "mem_dump_obj",
      "external": true,
      "loc": "mm/util.c:1039",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585136,
      "name": "mem_dump_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mem_dump_obj(void * object)
```

```json
{
  "name": "mem_dump_obj",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582792416,
      "name": "mem_dump_obj",
      "external": true,
      "loc": "mm/util.c:1062",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792416,
      "name": "mem_dump_obj",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_dump_obj(void * object)
```

```json
{
  "name": "mem_dump_obj",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582967456,
      "name": "mem_dump_obj",
      "external": true,
      "loc": "mm/util.c:1070",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967456,
      "name": "mem_dump_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void mem_dump_obj(void * object)
```
</details>
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
