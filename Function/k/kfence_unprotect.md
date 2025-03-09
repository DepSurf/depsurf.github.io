# Function: <code>kfence_unprotect</code>

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
bool kfence_unprotect(long unsigned int addr)
```

```json
{
  "name": "kfence_unprotect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236112,
      "name": "kfence_unprotect",
      "external": false,
      "loc": "mm/kfence/core.c:135",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236112,
      "name": "kfence_unprotect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfence_unprotect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582711145,
      "name": "kfence_unprotect",
      "external": false,
      "loc": "mm/kfence/core.c:238",
      "file": "mm/kfence/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_alloc"
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
  "name": "kfence_unprotect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583236969,
      "name": "kfence_unprotect",
      "external": false,
      "loc": "mm/kfence/core.c:237",
      "file": "mm/kfence/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_alloc"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kfence_unprotect(long unsigned int addr)
```

```json
{
  "name": "kfence_unprotect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583456610,
      "name": "kfence_unprotect",
      "external": false,
      "loc": "mm/kfence/core.c:237",
      "file": "mm/kfence/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_handle_page_fault"
      ],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452208,
      "name": "kfence_unprotect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfence_unprotect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583649628,
      "name": "kfence_unprotect",
      "external": false,
      "loc": "mm/kfence/core.c:245",
      "file": "mm/kfence/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_alloc"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool kfence_unprotect(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool kfence_unprotect(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool kfence_unprotect(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool kfence_unprotect(long unsigned int addr)
```
</details>
</li>
</ul>
