# Function: <code>landlock_insert_rule</code>

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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const u32 access)
```

```json
{
  "name": "landlock_insert_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317696,
      "name": "landlock_insert_rule",
      "external": true,
      "loc": "security/landlock/ruleset.c:230",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317696,
      "name": "landlock_insert_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const u32 access)
```

```json
{
  "name": "landlock_insert_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704448,
      "name": "landlock_insert_rule",
      "external": true,
      "loc": "security/landlock/ruleset.c:230",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704448,
      "name": "landlock_insert_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const access_mask_t access)
```

```json
{
  "name": "landlock_insert_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585369216,
      "name": "landlock_insert_rule",
      "external": true,
      "loc": "security/landlock/ruleset.c:231",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369216,
      "name": "landlock_insert_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const access_mask_t access)
```

```json
{
  "name": "landlock_insert_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120048,
      "name": "landlock_insert_rule",
      "external": true,
      "loc": "security/landlock/ruleset.c:231",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120048,
      "name": "landlock_insert_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const access_mask_t access)
```

```json
{
  "name": "landlock_insert_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586358544,
      "name": "landlock_insert_rule",
      "external": true,
      "loc": "security/landlock/ruleset.c:231",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:landlock_append_fs_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586358544,
      "name": "landlock_insert_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_id id, const access_mask_t access)
```

```json
{
  "name": "landlock_insert_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626496,
      "name": "landlock_insert_rule",
      "external": true,
      "loc": "security/landlock/ruleset.c:294",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/fs.c:landlock_append_fs_rule",
        "security/landlock/net.c:landlock_append_net_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626496,
      "name": "landlock_insert_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int landlock_insert_rule(const struct landlock_ruleset * ruleset, const struct landlock_object * object, const u32 access)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const u32 access</code> ➡️ <code>const access_mask_t access</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct landlock_id id</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct landlock_object * object</code>
</li>
</ul>
</details>
</li>
</ul>
