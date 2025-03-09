# Function: <code>create_rule</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```

```json
{
  "name": "create_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316112,
      "name": "create_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:69",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:insert_rule",
        "security/landlock/ruleset.c:insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316112,
      "name": "create_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```

```json
{
  "name": "create_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584703184,
      "name": "create_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:69",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:insert_rule",
        "security/landlock/ruleset.c:insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703184,
      "name": "create_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```

```json
{
  "name": "create_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585367648,
      "name": "create_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:72",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:insert_rule",
        "security/landlock/ruleset.c:insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585367648,
      "name": "create_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```

```json
{
  "name": "create_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118400,
      "name": "create_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:72",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:insert_rule",
        "security/landlock/ruleset.c:insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118400,
      "name": "create_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```

```json
{
  "name": "create_rule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:72",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:insert_rule",
        "security/landlock/ruleset.c:insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586357168,
      "name": "create_rule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071596624552,
      "name": "create_rule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "create_rule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586624432,
      "name": "create_rule",
      "external": false,
      "loc": "security/landlock/ruleset.c:99",
      "file": "security/landlock/ruleset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/ruleset.c:insert_rule",
        "security/landlock/ruleset.c:insert_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586624432,
      "name": "create_rule.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct landlock_rule * create_rule(const struct landlock_object * object, const const struct landlock_layer[0] * layers, const u32 num_layers, const const struct landlock_layer * new_layer)
```
</details>
</li>
</ul>
