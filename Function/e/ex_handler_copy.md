# Function: <code>ex_handler_copy</code>

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
bool ex_handler_copy(const struct exception_table_entry * fixup, struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "ex_handler_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406784,
      "name": "ex_handler_copy",
      "external": true,
      "loc": "arch/x86/mm/extable.c:84",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406784,
      "name": "ex_handler_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool ex_handler_copy(const struct exception_table_entry * fixup, struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "ex_handler_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409984,
      "name": "ex_handler_copy",
      "external": true,
      "loc": "arch/x86/mm/extable.c:84",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409984,
      "name": "ex_handler_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool ex_handler_copy(const struct exception_table_entry * fixup, struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```

```json
{
  "name": "ex_handler_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ex_handler_copy",
      "external": true,
      "loc": "arch/x86/mm/extable.c:84",
      "file": "arch/x86/mm/extable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592087395,
      "name": "ex_handler_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579472672,
      "name": "ex_handler_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
  "name": "ex_handler_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579550628,
      "name": "ex_handler_copy",
      "external": false,
      "loc": "arch/x86/mm/extable.c:87",
      "file": "arch/x86/mm/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/extable.c:fixup_exception"
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
  "name": "ex_handler_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579657123,
      "name": "ex_handler_copy",
      "external": false,
      "loc": "arch/x86/mm/extable.c:140",
      "file": "arch/x86/mm/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/extable.c:fixup_exception"
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
  "name": "ex_handler_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579671525,
      "name": "ex_handler_copy",
      "external": false,
      "loc": "arch/x86/mm/extable.c:166",
      "file": "arch/x86/mm/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/extable.c:fixup_exception"
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
  "name": "ex_handler_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579705413,
      "name": "ex_handler_copy",
      "external": false,
      "loc": "arch/x86/mm/extable.c:166",
      "file": "arch/x86/mm/extable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/extable.c:fixup_exception"
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
bool ex_handler_copy(const struct exception_table_entry * fixup, struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
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
bool ex_handler_copy(const struct exception_table_entry * fixup, struct pt_regs * regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr)
```
</details>
</li>
</ul>
