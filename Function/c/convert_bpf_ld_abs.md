# Function: <code>convert_bpf_ld_abs</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587964400,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:446",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964400,
      "name": "convert_bpf_ld_abs.isra.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588115280,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115280,
      "name": "convert_bpf_ld_abs.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588433504,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433504,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588639376,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588639376,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589473632,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:436",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589473632,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589474496,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:466",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589474496,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372912,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:466",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372912,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590103296,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:467",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590103296,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591654320,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:468",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654320,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593438192,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:470",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593438192,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593903088,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:470",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593903088,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594686432,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:475",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594686432,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502183872,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502183872,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234907272,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234907272,
      "name": "convert_bpf_ld_abs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295661888,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295661888,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278439682,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278439682,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246112,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246112,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587958928,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587958928,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588577936,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577936,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "convert_bpf_ld_abs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588715424,
      "name": "convert_bpf_ld_abs",
      "external": false,
      "loc": "net/core/filter.c:447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_convert_filter",
        "net/core/filter.c:bpf_convert_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715424,
      "name": "convert_bpf_ld_abs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter * fp, struct bpf_insn * * insnp)
```
</details>
</li>
</ul>
