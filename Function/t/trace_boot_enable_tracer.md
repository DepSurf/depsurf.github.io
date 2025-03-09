# Function: <code>trace_boot_enable_tracer</code>

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
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609219142,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:266",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void trace_boot_enable_tracer(struct trace_array * tr, struct xbc_node * node)
```

```json
{
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612285805,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:276",
      "file": "kernel/trace/trace_boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612285805,
      "name": "trace_boot_enable_tracer",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614425801,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:276",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
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
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615365275,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:592",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
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
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617152571,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:592",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627834719,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:592",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619598927,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:592",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_boot_enable_tracer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621902463,
      "name": "trace_boot_enable_tracer",
      "external": false,
      "loc": "kernel/trace/trace_boot.c:592",
      "file": "kernel/trace/trace_boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_boot.c:trace_boot_init_one_instance"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void trace_boot_enable_tracer(struct trace_array * tr, struct xbc_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void trace_boot_enable_tracer(struct trace_array * tr, struct xbc_node * node)
```
</details>
</li>
</ul>
