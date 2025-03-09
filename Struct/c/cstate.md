# Struct: <code>cstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    int state;
    uint32_t rep0;
    uint32_t rep1;
    uint32_t rep2;
    uint32_t rep3;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cstate {
    byte_t cs_this;
    bool initialized;
    struct cstate * next;
    struct iphdr cs_ip;
    struct tcphdr cs_tcp;
    unsigned char[64] cs_ipopt;
    unsigned char[64] cs_tcpopt;
    int cs_hsize;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>byte_t cs_this</code>
</li>
<li>
<b>Field added. </b>
<code>struct cstate * next</code>
</li>
<li>
<b>Field added. </b>
<code>struct iphdr cs_ip</code>
</li>
<li>
<b>Field added. </b>
<code>struct tcphdr cs_tcp</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char[64] cs_ipopt</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char[64] cs_tcpopt</code>
</li>
<li>
<b>Field added. </b>
<code>int cs_hsize</code>
</li>
<li>
<b>Field removed. </b>
<code>int state</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep0</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep1</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep2</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep3</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool initialized</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int state</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t rep0</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t rep1</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t rep2</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t rep3</code>
</li>
<li>
<b>Field removed. </b>
<code>byte_t cs_this</code>
</li>
<li>
<b>Field removed. </b>
<code>bool initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cstate * next</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iphdr cs_ip</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tcphdr cs_tcp</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char[64] cs_ipopt</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char[64] cs_tcpopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int cs_hsize</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>byte_t cs_this</code>
</li>
<li>
<b>Field added. </b>
<code>bool initialized</code>
</li>
<li>
<b>Field added. </b>
<code>struct cstate * next</code>
</li>
<li>
<b>Field added. </b>
<code>struct iphdr cs_ip</code>
</li>
<li>
<b>Field added. </b>
<code>struct tcphdr cs_tcp</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char[64] cs_ipopt</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char[64] cs_tcpopt</code>
</li>
<li>
<b>Field added. </b>
<code>int cs_hsize</code>
</li>
<li>
<b>Field removed. </b>
<code>int state</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep0</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep1</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep2</code>
</li>
<li>
<b>Field removed. </b>
<code>uint32_t rep3</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
