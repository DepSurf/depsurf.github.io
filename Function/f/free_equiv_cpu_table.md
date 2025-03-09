# Function: <code>free_equiv_cpu_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596339811,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:735",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596568367,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:747",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579176807,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:748",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071598513962,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:560",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604883626,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:567",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605086464,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:575",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192000,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:745",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192000,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204864,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204864,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207120,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207120,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579227728,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227728,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221232,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:742",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221232,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579223744,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:742",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223744,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579262320,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:742",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262320,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316725,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:748",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313968,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579382517,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:759",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579391909,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:754",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071626349568,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:727",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205968,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205968,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140720,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140720,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207040,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207040,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void free_equiv_cpu_table()
```

```json
{
  "name": "free_equiv_cpu_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212320,
      "name": "free_equiv_cpu_table",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/amd.c:743",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212320,
      "name": "free_equiv_cpu_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void free_equiv_cpu_table()
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void free_equiv_cpu_table()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void free_equiv_cpu_table()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void free_equiv_cpu_table()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void free_equiv_cpu_table()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_equiv_cpu_table()
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
