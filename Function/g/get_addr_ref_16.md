# Function: <code>get_addr_ref_16</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588821683,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1138",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589199721,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1138",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589441273,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1138",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589899417,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1141",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590125401,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1141",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585129248,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1145",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585129248,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280304,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1190",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280304,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585163744,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1192",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163744,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616960,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1192",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616960,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586774816,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1234",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586774816,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595940528,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1234",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595940528,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596458832,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1234",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596458832,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597353856,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1234",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597353856,
      "name": "get_addr_ref_16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589727657,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1141",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589453353,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1141",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590171033,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1141",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
  "name": "get_addr_ref_16",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590221481,
      "name": "get_addr_ref_16",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:1141",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_addr_ref"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * get_addr_ref_16(struct insn * insn, struct pt_regs * regs)
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
