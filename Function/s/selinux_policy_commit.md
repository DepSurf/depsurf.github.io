# Function: <code>selinux_policy_commit</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void selinux_policy_commit(struct selinux_state * state, struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2189",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591366695,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071583993728,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void selinux_policy_commit(struct selinux_state * state, struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2209",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309641,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071584020656,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
void selinux_policy_commit(struct selinux_state * state, struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2215",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300526,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071584390368,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
void selinux_policy_commit(struct selinux_state * state, struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2216",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594081834,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585016128,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
void selinux_policy_commit(struct selinux_state * state, struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2209",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096846,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585733408,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
void selinux_policy_commit(struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2173",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620049,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585964208,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
void selinux_policy_commit(struct selinux_load_state * load_state)
```

```json
{
  "name": "selinux_policy_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_policy_commit",
      "external": true,
      "loc": "security/selinux/ss/services.c:2183",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525719,
      "name": "selinux_policy_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586213056,
      "name": "selinux_policy_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void selinux_policy_commit(struct selinux_state * state, struct selinux_load_state * load_state)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, load_state</code> ➡️ <code>load_state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
