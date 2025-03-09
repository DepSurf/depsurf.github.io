# Function: <code>copy_array</code>

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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602668129,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:73",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602839367,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:77",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604635776,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:77",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604733058,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604746431,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609092280,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609092280,
      "name": "copy_array",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 36
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
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612157066,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612157066,
      "name": "copy_array",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 36
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
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614297197,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614297197,
      "name": "copy_array",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615223845,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ]
    },
    {
      "addr": 18446744071581162128,
      "name": "copy_array",
      "external": false,
      "loc": "kernel/bpf/verifier.c:752",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615223845,
      "name": "copy_array",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581162128,
      "name": "copy_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616997999,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ]
    },
    {
      "addr": 18446744071581437568,
      "name": "copy_array",
      "external": false,
      "loc": "kernel/bpf/verifier.c:979",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_verifier_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616997999,
      "name": "copy_array",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071581437568,
      "name": "copy_array",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627624446,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581793296,
      "name": "copy_array",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1168",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_func_state",
        "kernel/bpf/verifier.c:copy_func_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793296,
      "name": "copy_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619380542,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965232,
      "name": "copy_array",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1545",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_func_state",
        "kernel/bpf/verifier.c:copy_func_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965232,
      "name": "copy_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void copy_array(const void * src, void * target, unsigned int size)
```

```json
{
  "name": "copy_array",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621675646,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091088,
      "name": "copy_array",
      "external": false,
      "loc": "kernel/bpf/verifier.c:1186",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:prepare_func_exit",
        "kernel/bpf/verifier.c:setup_func_entry",
        "kernel/bpf/verifier.c:copy_verifier_state",
        "kernel/bpf/verifier.c:copy_func_state",
        "kernel/bpf/verifier.c:copy_func_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091088,
      "name": "copy_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604672734,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604640423,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604750497,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
  "name": "copy_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604750530,
      "name": "copy_array",
      "external": false,
      "loc": "arch/x86/kernel/cpu/hypervisor.c:84",
      "file": "arch/x86/kernel/cpu/hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform",
        "arch/x86/kernel/cpu/hypervisor.c:init_hypervisor_platform"
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
void copy_array(const void * src, void * target, unsigned int size)
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
