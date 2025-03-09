# Function: <code>srcu_invoke_callbacks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579778876,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcu.c:618",
      "file": "kernel/rcu/srcu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcu.c:process_srcu"
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
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579804219,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcu.c:618",
      "file": "kernel/rcu/srcu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcu.c:process_srcu"
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
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579832603,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcu.c:618",
      "file": "kernel/rcu/srcu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcu.c:process_srcu"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834336,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1132",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834336,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874624,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1133",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874624,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908544,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1163",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908544,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956096,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1181",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956096,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996400,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1156",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996400,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046528,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046528,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102752,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1172",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102752,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084288,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1161",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084288,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084928,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1246",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084928,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1241",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221344,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071592141506,
      "name": "srcu_invoke_callbacks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1536",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382272,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071593912591,
      "name": "srcu_invoke_callbacks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1605",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609136,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071595990811,
      "name": "srcu_invoke_callbacks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1681",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682864,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071596508967,
      "name": "srcu_invoke_callbacks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1701",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749648,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071597406685,
      "name": "srcu_invoke_callbacks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491247464,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491247464,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225256428,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225256428,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284152304,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284152304,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271776528,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271776528,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015264,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015264,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953984,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953984,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006800,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006800,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void srcu_invoke_callbacks(struct work_struct * work)
```

```json
{
  "name": "srcu_invoke_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049136,
      "name": "srcu_invoke_callbacks",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:1157",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049136,
      "name": "srcu_invoke_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void srcu_invoke_callbacks(struct work_struct * work)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
