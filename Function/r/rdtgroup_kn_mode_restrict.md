# Function: <code>rdtgroup_kn_mode_restrict</code>

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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206176,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1533",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206176,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219888,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1531",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219888,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222208,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1529",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222208,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246928,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1620",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246928,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240096,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1680",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_user_restrict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240096,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240368,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1680",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240368,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277760,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1640",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277760,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331760,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1640",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331760,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400144,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1645",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400144,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412272,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1926",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412272,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441232,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2017",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441232,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221056,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1529",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221056,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155984,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1529",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155984,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222128,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1529",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222128,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```

```json
{
  "name": "rdtgroup_kn_mode_restrict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227520,
      "name": "rdtgroup_kn_mode_restrict",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1529",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227520,
      "name": "rdtgroup_kn_mode_restrict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdtgroup_kn_mode_restrict(struct rdtgroup * r, const char * name)
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
