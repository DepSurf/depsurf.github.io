# Function: <code>trace_uprobe_create</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:426",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671248,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1618
    },
    {
      "addr": 18446744071580673492,
      "name": "trace_uprobe_create.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:434",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732512,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
    },
    {
      "addr": 18446744071580738014,
      "name": "trace_uprobe_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783136,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2020
    },
    {
      "addr": 18446744071580788753,
      "name": "trace_uprobe_create.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901104,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901104,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1283
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
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895360,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895360,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_uprobe_create(const char * raw_command)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580893104,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:719",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893104,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_uprobe_create(const char * raw_command)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094656,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:719",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094656,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_uprobe_create(const char * raw_command)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581356864,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:717",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356864,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_uprobe_create(const char * raw_command)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581691760,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:723",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691760,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_uprobe_create(const char * raw_command)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581836736,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:723",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836736,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trace_uprobe_create(const char * raw_command)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960208,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:719",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960208,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492092520,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492092520,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
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
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225994952,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225994952,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2008
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
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285294336,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285294336,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3012
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751936,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2020
    },
    {
      "addr": 18446744071580757553,
      "name": "trace_uprobe_create.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698128,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2020
    },
    {
      "addr": 18446744071580703745,
      "name": "trace_uprobe_create.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743184,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2020
    },
    {
      "addr": 18446744071580748801,
      "name": "trace_uprobe_create.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
```

```json
{
  "name": "trace_uprobe_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_uprobe_create",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:533",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801200,
      "name": "trace_uprobe_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2020
    },
    {
      "addr": 18446744071580806849,
      "name": "trace_uprobe_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int trace_uprobe_create(int argc, const char * * argv)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * raw_command</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * * argv</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int trace_uprobe_create(int argc, const char * * argv)
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
