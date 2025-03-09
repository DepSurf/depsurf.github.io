# Function: <code>kvm_send_ipi_mask_allbutself</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:509",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315808,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579317811,
      "name": "kvm_send_ipi_mask_allbutself.cold.19",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:493",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_send_ipi_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331040,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579333051,
      "name": "kvm_send_ipi_mask_allbutself.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:493",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335248,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579337242,
      "name": "kvm_send_ipi_mask_allbutself.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579364672,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:517",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364672,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363696,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:540",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363696,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369024,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:538",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369024,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430016,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:541",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430016,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498432,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:562",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498432,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594816,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:561",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594816,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:561",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607520,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071596485243,
      "name": "kvm_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:562",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637136,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071597381853,
      "name": "kvm_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:493",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331152,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579333146,
      "name": "kvm_send_ipi_mask_allbutself.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:493",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265584,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579267846,
      "name": "kvm_send_ipi_mask_allbutself.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:493",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331072,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579333066,
      "name": "kvm_send_ipi_mask_allbutself.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```

```json
{
  "name": "kvm_send_ipi_mask_allbutself",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kvm_send_ipi_mask_allbutself",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:493",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339616,
      "name": "kvm_send_ipi_mask_allbutself",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071579341370,
      "name": "kvm_send_ipi_mask_allbutself.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
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
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask * mask, int vector)
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
