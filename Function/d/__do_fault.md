# Function: <code>__do_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __do_fault(struct vm_area_struct * vma, long unsigned int address, long unsigned int pgoff, unsigned int flags, struct page * cow_page, struct page * * page)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664016,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:2759",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664016,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __do_fault(struct fault_env * fe, long unsigned int pgoff, struct page * cow_page, struct page * * page, void * * entry)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774128,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:2846",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774128,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838976,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:2866",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838976,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580884576,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3042",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884576,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580978320,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3211",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978320,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581111984,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3256",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111984,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192496,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:2994",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192496,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265360,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3057",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265360,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324208,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324208,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515312,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3448",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_shared_fault",
        "mm/memory.c:do_cow_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515312,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560240,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3607",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_shared_fault",
        "mm/memory.c:do_cow_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560240,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581583872,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3696",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583872,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581849552,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3832",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849552,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262432,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:4140",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262432,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754288,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:4141",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754288,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969776,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:4173",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_read_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969776,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583149744,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:4370",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149744,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492730512,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492730512,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226561120,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226561120,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286076816,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286076816,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272719384,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272719384,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293056,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293056,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237472,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237472,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284256,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284256,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
vm_fault_t __do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "__do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348208,
      "name": "__do_fault",
      "external": false,
      "loc": "mm/memory.c:3082",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348208,
      "name": "__do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fault_env * fe</code>
</li>
<li>
<b>Param added. </b>
<code>void * * entry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, address, pgoff, flags, cow_page, page</code> ➡️ <code>fe, pgoff, cow_page, page, entry</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env * fe</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int pgoff</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * cow_page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * * page</code>
</li>
<li>
<b>Param removed. </b>
<code>void * * entry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
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
