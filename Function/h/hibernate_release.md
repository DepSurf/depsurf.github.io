# Function: <code>hibernate_release</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579982408,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:77",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978992,
      "name": "hibernate_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964774,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:77",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965104,
      "name": "hibernate_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579967414,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:77",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967744,
      "name": "hibernate_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098518,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:78",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098848,
      "name": "hibernate_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580237029,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:77",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237344,
      "name": "hibernate_release",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580430922,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:77",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431264,
      "name": "hibernate_release",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503734,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:78",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500496,
      "name": "hibernate_release",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hibernate_release()
```

```json
{
  "name": "hibernate_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580563607,
      "name": "hibernate_release",
      "external": true,
      "loc": "kernel/power/hibernate.c:78",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate_quiet_exec",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560384,
      "name": "hibernate_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void hibernate_release()
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
