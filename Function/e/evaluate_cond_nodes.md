# Function: <code>evaluate_cond_nodes</code>

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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583885312,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_preserve_bools",
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885312,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584005184,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_preserve_bools",
        "security/selinux/ss/services.c:security_set_bools"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005184,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591310079,
      "name": "evaluate_cond_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584032176,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592301496,
      "name": "evaluate_cond_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584403472,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594082780,
      "name": "evaluate_cond_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585030064,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748336,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748336,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978960,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978960,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void evaluate_cond_nodes(struct policydb * p)
```

```json
{
  "name": "evaluate_cond_nodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226240,
      "name": "evaluate_cond_nodes",
      "external": true,
      "loc": "security/selinux/ss/conditional.c:123",
      "file": "security/selinux/ss/conditional.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226240,
      "name": "evaluate_cond_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void evaluate_cond_nodes(struct policydb * p)
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
