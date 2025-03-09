# Function: <code>__bpf_arch_text_poke</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr, const bool text_live)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:283",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509232,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
    },
    {
      "addr": 18446744071579513441,
      "name": "__bpf_arch_text_poke.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr, const bool text_live)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:317",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup",
        "arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483616,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071591276159,
      "name": "__bpf_arch_text_poke.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr, const bool text_live)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:329",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup",
        "arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485216,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071591218896,
      "name": "__bpf_arch_text_poke.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr, const bool text_live)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:325",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549440,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071592096945,
      "name": "__bpf_arch_text_poke.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:348",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638464,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071593864279,
      "name": "__bpf_arch_text_poke.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755984,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:356",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755984,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802576,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:356",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802576,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr)
```

```json
{
  "name": "__bpf_arch_text_poke",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837056,
      "name": "__bpf_arch_text_poke",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:478",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837056,
      "name": "__bpf_arch_text_poke",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int __bpf_arch_text_poke(void * ip, enum bpf_text_poke_type t, void * old_addr, void * new_addr, const bool text_live)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const bool text_live</code>
</li>
</ul>
</details>
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
