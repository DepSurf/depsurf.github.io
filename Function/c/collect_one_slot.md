# Function: <code>collect_one_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580079552,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:204",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/kprobes.c:__free_insn_slot"
      ],
      "caller_func": [
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/kprobes.c:__free_insn_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079552,
      "name": "collect_one_slot.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int collect_one_slot(struct kprobe_insn_page * kip, int idx)
```

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112768,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:204",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112768,
      "name": "collect_one_slot",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int collect_one_slot(struct kprobe_insn_page * kip, int idx)
```

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153088,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:204",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153088,
      "name": "collect_one_slot",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163967,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158528,
      "name": "collect_one_slot.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580216639,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211424,
      "name": "collect_one_slot.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580276671,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271312,
      "name": "collect_one_slot.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580328927,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324032,
      "name": "collect_one_slot.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381498,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376400,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580430437,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425152,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580511958,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:197",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505568,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499890,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:194",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580492416,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503970,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:195",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496208,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580671586,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:195",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663808,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580881349,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874400,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581170837,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163648,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581265269,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257376,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581371557,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:205",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363616,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491698588,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491691864,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225651108,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225645652,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284717136,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284708496,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
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
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580399237,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393952,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580346405,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341120,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580390485,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385200,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_one_slot",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580446007,
      "name": "collect_one_slot",
      "external": false,
      "loc": "kernel/kprobes.c:192",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ],
      "caller_func": [
        "kernel/kprobes.c:__free_insn_slot",
        "kernel/kprobes.c:collect_garbage_slots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440704,
      "name": "collect_one_slot.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int collect_one_slot(struct kprobe_insn_page * kip, int idx)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int collect_one_slot(struct kprobe_insn_page * kip, int idx)
```
</details>
</li>
</ul>
