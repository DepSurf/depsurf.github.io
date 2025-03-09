# Function: <code>copy_from_buffer</code>

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
int copy_from_buffer(void * dst, unsigned int offset, unsigned int size, const void * kbuf, const void * ubuf)
```

```json
{
  "name": "copy_from_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152656,
      "name": "copy_from_buffer",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:1081",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152656,
      "name": "copy_from_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int copy_from_buffer(void * dst, unsigned int offset, unsigned int size, const void * kbuf, const void * ubuf)
```

```json
{
  "name": "copy_from_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194608,
      "name": "copy_from_buffer",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:1186",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194608,
      "name": "copy_from_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int copy_from_buffer(void * dst, unsigned int offset, unsigned int size, const void * kbuf, const void * ubuf)
```

```json
{
  "name": "copy_from_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250928,
      "name": "copy_from_buffer",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:1190",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250928,
      "name": "copy_from_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int copy_from_buffer(void * dst, unsigned int offset, unsigned int size, const void * kbuf, const void * ubuf)
```

```json
{
  "name": "copy_from_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579257408,
      "name": "copy_from_buffer",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:1195",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257408,
      "name": "copy_from_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int copy_from_buffer(void * dst, unsigned int offset, unsigned int size, const void * kbuf, const void * ubuf)
```

```json
{
  "name": "copy_from_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287248,
      "name": "copy_from_buffer",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:1194",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287248,
      "name": "copy_from_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int copy_from_buffer(void * dst, unsigned int offset, unsigned int size, const void * kbuf, const void * ubuf)
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
