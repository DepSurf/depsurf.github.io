# Function: <code>__static_key_slow_dec_cpuslocked</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580713712,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:183",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713712,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void __static_key_slow_dec_cpuslocked(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580845824,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:184",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845824,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580914624,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:205",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_deferred",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914624,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581012912,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012912,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581069296,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069296,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250711,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249088,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292791,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291056,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581310423,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308720,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581555556,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553760,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581907047,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905472,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582341495,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339792,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582543863,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541760,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582713095,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:267",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710912,
      "name": "__static_key_slow_dec_cpuslocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492430152,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492430152,
      "name": "__static_key_slow_dec_cpuslocked",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285698448,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285698448,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038144,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038144,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580984224,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984224,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029344,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029344,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```

```json
{
  "name": "__static_key_slow_dec_cpuslocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090768,
      "name": "__static_key_slow_dec_cpuslocked",
      "external": false,
      "loc": "kernel/jump_label.c:239",
      "file": "kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec_cpuslocked",
        "kernel/jump_label.c:static_key_slow_dec",
        "kernel/jump_label.c:jump_label_update_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090768,
      "name": "__static_key_slow_dec_cpuslocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __static_key_slow_dec_cpuslocked(struct static_key * key, long unsigned int rate_limit, struct delayed_work * work)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int rate_limit</code>
</li>
<li>
<b>Param removed. </b>
<code>struct delayed_work * work</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __static_key_slow_dec_cpuslocked(struct static_key * key)
```
</details>
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
