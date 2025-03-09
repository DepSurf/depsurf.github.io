# Function: <code>hook_sb_delete</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hook_sb_delete(const struct super_block * sb)
```

```json
{
  "name": "hook_sb_delete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584320896,
      "name": "hook_sb_delete",
      "external": false,
      "loc": "security/landlock/fs.c:344",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584320896,
      "name": "hook_sb_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071584321456,
      "name": "hook_sb_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hook_sb_delete(const struct super_block * sb)
```

```json
{
  "name": "hook_sb_delete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584708000,
      "name": "hook_sb_delete",
      "external": false,
      "loc": "security/landlock/fs.c:344",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708000,
      "name": "hook_sb_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071584708560,
      "name": "hook_sb_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071592307650,
      "name": "hook_sb_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hook_sb_delete(const struct super_block * sb)
```

```json
{
  "name": "hook_sb_delete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585371088,
      "name": "hook_sb_delete",
      "external": false,
      "loc": "security/landlock/fs.c:912",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371088,
      "name": "hook_sb_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071585371696,
      "name": "hook_sb_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071594089146,
      "name": "hook_sb_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hook_sb_delete(const struct super_block * sb)
```

```json
{
  "name": "hook_sb_delete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586122304,
      "name": "hook_sb_delete",
      "external": false,
      "loc": "security/landlock/fs.c:927",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122304,
      "name": "hook_sb_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071586122928,
      "name": "hook_sb_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071596101373,
      "name": "hook_sb_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hook_sb_delete(const struct super_block * sb)
```

```json
{
  "name": "hook_sb_delete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586361056,
      "name": "hook_sb_delete",
      "external": false,
      "loc": "security/landlock/fs.c:927",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361056,
      "name": "hook_sb_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071586361680,
      "name": "hook_sb_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071596624587,
      "name": "hook_sb_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hook_sb_delete(const struct super_block * sb)
```

```json
{
  "name": "hook_sb_delete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586630144,
      "name": "hook_sb_delete",
      "external": false,
      "loc": "security/landlock/fs.c:844",
      "file": "security/landlock/fs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630144,
      "name": "hook_sb_delete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071586630768,
      "name": "hook_sb_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071597531023,
      "name": "hook_sb_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void hook_sb_delete(const struct super_block * sb)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
