# Function: <code>check_reference_leak</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722464,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:2834",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722464,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800560,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3926",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800560,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851696,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851696,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982096,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4584",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982096,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988080,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5036",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988080,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995920,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5889",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995920,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209456,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209456,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493456,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7040",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493456,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:7799",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850240,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071596016793,
      "name": "check_reference_leak.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9235",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961024,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071596534370,
      "name": "check_reference_leak.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int check_reference_leak(struct bpf_verifier_env * env, bool exception_exit)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9943",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_abs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088880,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071597435584,
      "name": "check_reference_leak.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492176784,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492176784,
      "name": "check_reference_leak",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226074036,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226074036,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285391024,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285391024,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272332332,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272332332,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820496,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820496,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766672,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766672,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811744,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811744,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
```

```json
{
  "name": "check_reference_leak",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870128,
      "name": "check_reference_leak",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3929",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870128,
      "name": "check_reference_leak",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int check_reference_leak(struct bpf_verifier_env * env)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exception_exit</code>
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
