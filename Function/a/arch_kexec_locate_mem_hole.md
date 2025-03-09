# Function: <code>arch_kexec_locate_mem_hole</code>

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
int arch_kexec_locate_mem_hole(struct kexec_buf * kbuf)
```

```json
{
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580324176,
      "name": "arch_kexec_locate_mem_hole",
      "external": true,
      "loc": "kernel/kexec_file.c:652",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_add_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324176,
      "name": "arch_kexec_locate_mem_hole",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 114
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
int arch_kexec_locate_mem_hole(struct kexec_buf * kbuf)
```

```json
{
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327456,
      "name": "arch_kexec_locate_mem_hole",
      "external": true,
      "loc": "kernel/kexec_file.c:652",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_add_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327456,
      "name": "arch_kexec_locate_mem_hole",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 114
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
int arch_kexec_locate_mem_hole(struct kexec_buf * kbuf)
```

```json
{
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481968,
      "name": "arch_kexec_locate_mem_hole",
      "external": true,
      "loc": "kernel/kexec_file.c:652",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_add_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481968,
      "name": "arch_kexec_locate_mem_hole",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 114
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
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580676636,
      "name": "arch_kexec_locate_mem_hole",
      "external": false,
      "loc": "include/linux/kexec.h:234",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_add_buffer"
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
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580947644,
      "name": "arch_kexec_locate_mem_hole",
      "external": false,
      "loc": "include/linux/kexec.h:235",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_add_buffer"
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
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581034636,
      "name": "arch_kexec_locate_mem_hole",
      "external": false,
      "loc": "include/linux/kexec.h:227",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_add_buffer"
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
  "name": "arch_kexec_locate_mem_hole",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581132652,
      "name": "arch_kexec_locate_mem_hole",
      "external": false,
      "loc": "include/linux/kexec.h:224",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_add_buffer"
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
int arch_kexec_locate_mem_hole(struct kexec_buf * kbuf)
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int arch_kexec_locate_mem_hole(struct kexec_buf * kbuf)
```
</details>
</li>
</ul>
