# Function: <code>arch_copy_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579237736,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:403",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
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
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579237228,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:405",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
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
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579249676,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:406",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579245088,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:429",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245088,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579261568,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:448",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261568,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272672,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:450",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272672,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296832,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:448",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296832,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313296,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:446",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313296,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317440,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:446",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317440,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346320,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:452",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346320,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579345680,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:453",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345680,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350304,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:695",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350304,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408032,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:689",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408032,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474528,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:699",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474528,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567008,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:672",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567008,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579328,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:674",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579328,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579609120,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:709",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609120,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313344,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:446",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313344,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247936,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:446",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247936,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313264,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:446",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313264,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int arch_copy_kprobe(struct kprobe * p)
```

```json
{
  "name": "arch_copy_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321536,
      "name": "arch_copy_kprobe",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:446",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321536,
      "name": "arch_copy_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_copy_kprobe(struct kprobe * p)
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
