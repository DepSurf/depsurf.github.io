# Function: <code>unregister_jprobes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_jprobes(struct jprobe * * jps, int num)
```

```json
{
  "name": "unregister_jprobes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082832,
      "name": "unregister_jprobes",
      "external": true,
      "loc": "kernel/kprobes.c:1761",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:unregister_jprobe",
        "kernel/kprobes.c:register_jprobes"
      ],
      "caller_func": [
        "kernel/kprobes.c:unregister_jprobe",
        "kernel/kprobes.c:register_jprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082832,
      "name": "unregister_jprobes.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071580083008,
      "name": "unregister_jprobes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_jprobes(struct jprobe * * jps, int num)
```

```json
{
  "name": "unregister_jprobes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580116438,
      "name": "unregister_jprobes",
      "external": true,
      "loc": "kernel/kprobes.c:1761",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:unregister_jprobe",
        "kernel/kprobes.c:register_jprobes"
      ],
      "caller_func": [
        "kernel/kprobes.c:unregister_jprobe",
        "kernel/kprobes.c:register_jprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116240,
      "name": "unregister_jprobes.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071580116400,
      "name": "unregister_jprobes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_jprobes(struct jprobe * * jps, int num)
```

```json
{
  "name": "unregister_jprobes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580156758,
      "name": "unregister_jprobes",
      "external": true,
      "loc": "kernel/kprobes.c:1761",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:unregister_jprobe",
        "kernel/kprobes.c:register_jprobes"
      ],
      "caller_func": [
        "kernel/kprobes.c:unregister_jprobe",
        "kernel/kprobes.c:register_jprobes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156560,
      "name": "unregister_jprobes.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071580156720,
      "name": "unregister_jprobes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unregister_jprobes(struct jprobe * * jps, int num)
```

```json
{
  "name": "unregister_jprobes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161766,
      "name": "unregister_jprobes",
      "external": true,
      "loc": "kernel/kprobes.c:1821",
      "file": "kernel/kprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kprobes.c:unregister_jprobe"
      ],
      "caller_func": [
        "kernel/kprobes.c:unregister_jprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161568,
      "name": "unregister_jprobes.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071580161728,
      "name": "unregister_jprobes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void unregister_jprobes(struct jprobe * * jps, int num)
```
</details>
</li>
</ul>
