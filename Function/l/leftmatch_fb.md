# Function: <code>leftmatch_fb</code>

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
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583263501,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:651",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583381357,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:651",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583568097,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:647",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583673828,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584035808,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:703",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035808,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155056,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:703",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155056,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584182112,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:703",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182112,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584567136,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:703",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567136,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212784,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:701",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212784,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585944896,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:701",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944896,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586177344,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:657",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177344,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
```

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586428624,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:657",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586428624,
      "name": "leftmatch_fb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
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
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495468564,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228835020,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289522636,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274655886,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583642564,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583579620,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583626340,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "leftmatch_fb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583724404,
      "name": "leftmatch_fb",
      "external": false,
      "loc": "security/apparmor/match.c:662",
      "file": "security/apparmor/match.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/match.c:aa_dfa_leftmatch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
unsigned int leftmatch_fb(struct aa_dfa * dfa, unsigned int start, const char * str, struct match_workbuf * wb, unsigned int * count)
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
