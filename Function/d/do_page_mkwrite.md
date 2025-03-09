# Function: <code>do_page_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_area_struct * vma, struct page * page, long unsigned int address)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580663168,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:1958",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663168,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int do_page_mkwrite(struct vm_area_struct * vma, struct page * page, long unsigned int address)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773264,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2037",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773264,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580838000,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2037",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580838000,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883312,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2243",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883312,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976112,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2360",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976112,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111344,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2402",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111344,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190704,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2138",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190704,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263520,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2192",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263520,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322256,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322256,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515120,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2526",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_shared_fault",
        "mm/memory.c:wp_page_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515120,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560048,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2703",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_shared_fault",
        "mm/memory.c:wp_page_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560048,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581583680,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2764",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583680,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581849360,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2859",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849360,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582241552,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2952",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241552,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732160,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2932",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732160,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948512,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2931",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948512,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf, struct folio * folio)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583124288,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2956",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124288,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492729144,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492729144,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226561492,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226561492,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286074400,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286074400,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272719580,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272719580,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291104,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291104,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236096,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236096,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282304,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282304,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
vm_fault_t do_page_mkwrite(struct vm_fault * vmf)
```

```json
{
  "name": "do_page_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346144,
      "name": "do_page_mkwrite",
      "external": false,
      "loc": "mm/memory.c:2197",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346144,
      "name": "do_page_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
</ul>
</details>
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
