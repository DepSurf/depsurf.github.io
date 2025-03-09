# Function: <code>set_pages_state</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_pages_state(long unsigned int vaddr, unsigned int npages, int op)
```

```json
{
  "name": "set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593848408,
      "name": "set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:880",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517584,
      "name": "set_pages_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071593848408,
      "name": "set_pages_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void set_pages_state(long unsigned int vaddr, unsigned int npages, int op)
```

```json
{
  "name": "set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579617152,
      "name": "set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:880",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617152,
      "name": "set_pages_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_pages_state(long unsigned int vaddr, long unsigned int npages, int op)
```

```json
{
  "name": "set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632240,
      "name": "set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:837",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_accept_memory",
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632240,
      "name": "set_pages_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071579632336,
      "name": "set_pages_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_pages_state(long unsigned int vaddr, long unsigned int npages, int op)
```

```json
{
  "name": "set_pages_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661920,
      "name": "set_pages_state",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:864",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_accept_memory",
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661920,
      "name": "set_pages_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071579662016,
      "name": "set_pages_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void set_pages_state(long unsigned int vaddr, unsigned int npages, int op)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int npages</code> ➡️ <code>long unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
