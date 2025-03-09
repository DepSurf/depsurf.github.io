# Function: <code>copy_module_elf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580544304,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544304,
      "name": "copy_module_elf.isra.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580608408,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2013",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608408,
      "name": "copy_module_elf.isra.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580000402,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2040",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580046921,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2048",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580104920,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2047",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580152398,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2048",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580198522,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2045",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580246750,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2102",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293536,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2094",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293536,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277424,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2156",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277424,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580281712,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2066",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281712,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433472,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2068",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433472,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486272,
      "name": "copy_module_elf",
      "external": true,
      "loc": "kernel/module/livepatch.c:18",
      "file": "kernel/module/livepatch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486272,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737568,
      "name": "copy_module_elf",
      "external": true,
      "loc": "kernel/module/livepatch.c:18",
      "file": "kernel/module/livepatch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737568,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819664,
      "name": "copy_module_elf",
      "external": true,
      "loc": "kernel/module/livepatch.c:18",
      "file": "kernel/module/livepatch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819664,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int copy_module_elf(struct module * mod, struct load_info * info)
```

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909104,
      "name": "copy_module_elf",
      "external": true,
      "loc": "kernel/module/livepatch.c:18",
      "file": "kernel/module/livepatch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909104,
      "name": "copy_module_elf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2161",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2161",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284444708,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2102",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2161",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580215550,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2102",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580162990,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2102",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580207022,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2102",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
  "name": "copy_module_elf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580259476,
      "name": "copy_module_elf",
      "external": false,
      "loc": "kernel/module.c:2102",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
int copy_module_elf(struct module * mod, struct load_info * info)
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
