# Function: <code>print_bpf_insn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580370718,
      "name": "print_bpf_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:325",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
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
  "name": "print_bpf_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580430018,
      "name": "print_bpf_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:331",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
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
  "name": "print_bpf_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580481908,
      "name": "print_bpf_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:299",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
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
  "name": "print_bpf_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580507673,
      "name": "print_bpf_insn",
      "external": false,
      "loc": "kernel/bpf/verifier.c:307",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void print_bpf_insn(bpf_insn_print_cb verbose, struct bpf_verifier_env * env, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609280,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:95",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609280,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1189
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705600,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:125",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705600,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1431
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782176,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:125",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782176,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1431
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866992,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866992,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917952,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917952,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067040,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067040,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081024,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081024,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1439
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099456,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:131",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099456,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1833
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329024,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:131",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329024,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1900
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633424,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:131",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633424,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1989
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582021136,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:131",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582021136,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1989
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213392,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:131",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213392,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1946
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362480,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:169",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362480,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2320
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492252768,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492252768,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1528
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226144400,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226144400,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1596
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285481440,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285481440,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1960
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272394090,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:backtrack_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272394090,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1280
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886752,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886752,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832816,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832816,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580878000,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878000,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
void print_bpf_insn(const struct bpf_insn_cbs * cbs, const struct bpf_insn * insn, bool allow_ptr_leaks)
```

```json
{
  "name": "print_bpf_insn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936640,
      "name": "print_bpf_insn",
      "external": true,
      "loc": "kernel/bpf/disasm.c:117",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:__mark_chain_precision"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936640,
      "name": "print_bpf_insn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1427
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void print_bpf_insn(bpf_insn_print_cb verbose, struct bpf_verifier_env * env, const struct bpf_insn * insn, bool allow_ptr_leaks)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_insn_cbs * cbs</code>
</li>
<li>
<b>Param removed. </b>
<code>bpf_insn_print_cb verbose</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_env * env</code>
</li>
<li>
<b>Param reordered. </b>
<code>verbose, env, insn, allow_ptr_leaks</code> ➡️ <code>cbs, insn, allow_ptr_leaks</code>
</li>
</ul>
</details>
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
