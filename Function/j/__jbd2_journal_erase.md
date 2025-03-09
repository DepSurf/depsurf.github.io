# Function: <code>__jbd2_journal_erase</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __jbd2_journal_erase(journal_t * journal, unsigned int flags)
```

```json
{
  "name": "__jbd2_journal_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_erase",
      "external": false,
      "loc": "fs/jbd2/journal.c:1753",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827696,
      "name": "__jbd2_journal_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    },
    {
      "addr": 18446744071592275169,
      "name": "__jbd2_journal_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int __jbd2_journal_erase(journal_t * journal, unsigned int flags)
```

```json
{
  "name": "__jbd2_journal_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_erase",
      "external": false,
      "loc": "fs/jbd2/journal.c:1759",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395088,
      "name": "__jbd2_journal_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    },
    {
      "addr": 18446744071594057030,
      "name": "__jbd2_journal_erase.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int __jbd2_journal_erase(journal_t * journal, unsigned int flags)
```

```json
{
  "name": "__jbd2_journal_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049504,
      "name": "__jbd2_journal_erase",
      "external": false,
      "loc": "fs/jbd2/journal.c:1765",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049504,
      "name": "__jbd2_journal_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
int __jbd2_journal_erase(journal_t * journal, unsigned int flags)
```

```json
{
  "name": "__jbd2_journal_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585277456,
      "name": "__jbd2_journal_erase",
      "external": false,
      "loc": "fs/jbd2/journal.c:1779",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277456,
      "name": "__jbd2_journal_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int __jbd2_journal_erase(journal_t * journal, unsigned int flags)
```

```json
{
  "name": "__jbd2_journal_erase",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511024,
      "name": "__jbd2_journal_erase",
      "external": false,
      "loc": "fs/jbd2/journal.c:1950",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511024,
      "name": "__jbd2_journal_erase",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __jbd2_journal_erase(journal_t * journal, unsigned int flags)
```
</details>
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
