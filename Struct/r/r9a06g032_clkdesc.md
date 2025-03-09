# Struct: <code>r9a06g032_clkdesc</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct r9a06g032_clkdesc {
    const char * name;
    uint32_t managed;
    uint32_t type;
    uint32_t index;
    uint32_t source;
    struct r9a06g032_gate gate;
    unsigned int div_min;
    unsigned int div_max;
    unsigned int reg;
    u16[4] div_table;
    u16 div;
    u16 mul;
    unsigned int factor;
    unsigned int frequency;
    struct (anon) dual;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct r9a06g032_clkdesc {
    const char * name;
    uint32_t managed;
    uint32_t type;
    uint32_t index;
    uint32_t source;
    struct r9a06g032_gate gate;
    unsigned int div_min;
    unsigned int div_max;
    unsigned int reg;
    u16[4] div_table;
    u16 div;
    u16 mul;
    unsigned int factor;
    unsigned int frequency;
    struct (anon) dual;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct r9a06g032_clkdesc {
    const char * name;
    uint32_t managed;
    uint32_t type;
    uint32_t index;
    uint32_t source;
    struct r9a06g032_gate gate;
    unsigned int div_min;
    unsigned int div_max;
    unsigned int reg;
    u16[4] div_table;
    u16 div;
    u16 mul;
    unsigned int factor;
    unsigned int frequency;
    struct (anon) dual;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct r9a06g032_clkdesc {
    const char * name;
    uint32_t managed;
    uint32_t type;
    uint32_t index;
    uint32_t source;
    struct r9a06g032_gate gate;
    unsigned int div_min;
    unsigned int div_max;
    unsigned int reg;
    u16[4] div_table;
    u16 div;
    u16 mul;
    unsigned int factor;
    unsigned int frequency;
    struct (anon) dual;
}
```
</details>
</li>
</ul>
