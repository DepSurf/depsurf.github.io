# Function: <code>flush_tlb_func</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313648,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:101",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313648,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579312864,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:215",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312864,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579328080,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:230",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328080,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417888,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:663",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417888,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:722",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481200,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071592087961,
      "name": "flush_tlb_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:723",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560320,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
    },
    {
      "addr": 18446744071593854899,
      "name": "flush_tlb_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:723",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667648,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
    },
    {
      "addr": 18446744071595969592,
      "name": "flush_tlb_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:742",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681536,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    },
    {
      "addr": 18446744071596487190,
      "name": "flush_tlb_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void flush_tlb_func(void * info)
```

```json
{
  "name": "flush_tlb_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_func",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:743",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:arch_tlbbatch_flush",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715984,
      "name": "flush_tlb_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    },
    {
      "addr": 18446744071597383812,
      "name": "flush_tlb_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void flush_tlb_func(void * info)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void flush_tlb_func(void * info)
```
</details>
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
