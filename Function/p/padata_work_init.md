# Function: <code>padata_work_init</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581245898,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:99",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581288538,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:99",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581306363,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:99",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581551207,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:86",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581901944,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:86",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void padata_work_init(struct padata_work * pw, work_func_t work_fn, void * data, int flags)
```

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596417008,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:94",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596417008,
      "name": "padata_work_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void padata_work_init(struct padata_work * pw, work_func_t work_fn, void * data, int flags)
```

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596956960,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:94",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596956960,
      "name": "padata_work_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void padata_work_init(struct padata_work * pw, work_func_t work_fn, void * data, int flags)
```

```json
{
  "name": "padata_work_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597884480,
      "name": "padata_work_init",
      "external": false,
      "loc": "kernel/padata.c:94",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_multithreaded",
        "kernel/padata.c:padata_do_multithreaded"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597884480,
      "name": "padata_work_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void padata_work_init(struct padata_work * pw, work_func_t work_fn, void * data, int flags)
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
