# Function: <code>omem_charge</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588622884,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:96",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_alloc"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588843733,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589732533,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:100",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_alloc"
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502417964,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int omem_charge(struct sock * sk, unsigned int size)
```

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235151160,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:selem_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235151160,
      "name": "omem_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295969912,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278622770,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588450117,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588162805,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588782293,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "omem_charge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588922885,
      "name": "omem_charge",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:99",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_alloc",
        "net/core/bpf_sk_storage.c:selem_alloc"
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

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int omem_charge(struct sock * sk, unsigned int size)
```
</details>
</li>
</ul>
