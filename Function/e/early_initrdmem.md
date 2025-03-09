# Function: <code>early_initrdmem</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609008190,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:31",
      "file": "init/do_mounts_initrd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609008190,
      "name": "early_initrdmem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 101
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
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612072296,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:31",
      "file": "init/do_mounts_initrd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612072296,
      "name": "early_initrdmem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 101
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
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614210507,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:31",
      "file": "init/do_mounts_initrd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614210507,
      "name": "early_initrdmem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 101
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
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615129225,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:31",
      "file": "init/do_mounts_initrd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615129225,
      "name": "early_initrdmem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 101
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
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616891261,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:51",
      "file": "init/do_mounts_initrd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616891261,
      "name": "early_initrdmem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 123
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
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627483409,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:51",
      "file": "init/do_mounts_initrd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:early_initrd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627483232,
      "name": "early_initrdmem",
      "section": ".init.text",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619227329,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:51",
      "file": "init/do_mounts_initrd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:early_initrd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619227152,
      "name": "early_initrdmem",
      "section": ".init.text",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_initrdmem(char * p)
```

```json
{
  "name": "early_initrdmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621517217,
      "name": "early_initrdmem",
      "external": false,
      "loc": "init/do_mounts_initrd.c:51",
      "file": "init/do_mounts_initrd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/do_mounts_initrd.c:early_initrd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621517040,
      "name": "early_initrdmem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int early_initrdmem(char * p)
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
