# Function: <code>set_majmin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603584,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:268",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603584,
      "name": "set_majmin.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582850493,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:268",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848640,
      "name": "set_majmin.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582946522,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:268",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944688,
      "name": "set_majmin.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582996762,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:268",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994800,
      "name": "set_majmin.part.8",
      "section": ".text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583159088,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:260",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159088,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583364592,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:260",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364592,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583483344,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:260",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483344,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583669456,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669456,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583776464,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583776464,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584168964,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:261",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584288084,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:261",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584313172,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:261",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584700100,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:261",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585364278,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:262",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586114654,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:273",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586353627,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:273",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586351184,
      "name": "set_majmin",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586620731,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:273",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618240,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495578584,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495578584,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228940488,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228940488,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289675648,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289675648,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274746792,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274745174,
      "name": "set_majmin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745200,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745200,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583682256,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682256,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728976,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728976,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
```

```json
{
  "name": "set_majmin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583829760,
      "name": "set_majmin",
      "external": false,
      "loc": "security/device_cgroup.c:259",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829760,
      "name": "set_majmin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void set_majmin(char * str, unsigned int m)
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void set_majmin(char * str, unsigned int m)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void set_majmin(char * str, unsigned int m)
```
</details>
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
void set_majmin(char * str, unsigned int m)
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
