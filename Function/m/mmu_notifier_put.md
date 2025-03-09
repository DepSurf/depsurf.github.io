# Function: <code>mmu_notifier_put</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588832,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588832,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802576,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:879",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802576,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850224,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:895",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850224,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880592,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:895",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880592,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175984,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:895",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175984,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633824,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:895",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633824,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155104,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:895",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155104,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365456,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:895",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365456,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void mmu_notifier_put(struct mmu_notifier * subscription)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583602224,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:887",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602224,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493027024,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493027024,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226744380,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226744380,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286457120,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286457120,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272902266,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272902266,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557568,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557568,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499216,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499216,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581548880,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548880,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void mmu_notifier_put(struct mmu_notifier * mn)
```

```json
{
  "name": "mmu_notifier_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613952,
      "name": "mmu_notifier_put",
      "external": true,
      "loc": "mm/mmu_notifier.c:501",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_mirror_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613952,
      "name": "mmu_notifier_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void mmu_notifier_put(struct mmu_notifier * mn)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier * subscription</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mmu_notifier * mn</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
