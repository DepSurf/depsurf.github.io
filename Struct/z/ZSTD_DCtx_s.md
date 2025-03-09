# Struct: <code>ZSTD_DCtx_s</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const ZSTD_seqSymbol * LLTptr;
    const ZSTD_seqSymbol * MLTptr;
    const ZSTD_seqSymbol * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyDTables_t entropy;
    U32[640] workspace;
    const void * previousDstEnd;
    const void * prefixStart;
    const void * virtualStart;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameHeader fParams;
    U64 processedCSize;
    U64 decodedSize;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    ZSTD_format_e format;
    ZSTD_forceIgnoreChecksum_e forceIgnoreChecksum;
    U32 validateChecksum;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    size_t staticSize;
    int bmi2;
    ZSTD_DDict * ddictLocal;
    const ZSTD_DDict * ddict;
    U32 dictID;
    int ddictIsCold;
    ZSTD_dictUses_e dictUses;
    ZSTD_DDictHashSet * ddictSet;
    ZSTD_refMultipleDDicts_e refMultipleDDicts;
    ZSTD_dStreamStage streamStage;
    char * inBuff;
    size_t inBuffSize;
    size_t inPos;
    size_t maxWindowSize;
    char * outBuff;
    size_t outBuffSize;
    size_t outStart;
    size_t outEnd;
    size_t lhSize;
    void * legacyContext;
    U32 previousLegacyVersion;
    U32 legacyVersion;
    U32 hostageByte;
    int noForwardProgress;
    ZSTD_bufferMode_e outBufferMode;
    ZSTD_outBuffer expectedOutBuffer;
    BYTE[131104] litBuffer;
    BYTE[18] headerBuffer;
    size_t oversizedDuration;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const ZSTD_seqSymbol * LLTptr;
    const ZSTD_seqSymbol * MLTptr;
    const ZSTD_seqSymbol * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyDTables_t entropy;
    U32[640] workspace;
    const void * previousDstEnd;
    const void * prefixStart;
    const void * virtualStart;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameHeader fParams;
    U64 processedCSize;
    U64 decodedSize;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    ZSTD_format_e format;
    ZSTD_forceIgnoreChecksum_e forceIgnoreChecksum;
    U32 validateChecksum;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    size_t staticSize;
    int bmi2;
    ZSTD_DDict * ddictLocal;
    const ZSTD_DDict * ddict;
    U32 dictID;
    int ddictIsCold;
    ZSTD_dictUses_e dictUses;
    ZSTD_DDictHashSet * ddictSet;
    ZSTD_refMultipleDDicts_e refMultipleDDicts;
    ZSTD_dStreamStage streamStage;
    char * inBuff;
    size_t inBuffSize;
    size_t inPos;
    size_t maxWindowSize;
    char * outBuff;
    size_t outBuffSize;
    size_t outStart;
    size_t outEnd;
    size_t lhSize;
    U32 hostageByte;
    int noForwardProgress;
    ZSTD_bufferMode_e outBufferMode;
    ZSTD_outBuffer expectedOutBuffer;
    BYTE * litBuffer;
    const BYTE * litBufferEnd;
    ZSTD_litLocation_e litBufferLocation;
    BYTE[65568] litExtraBuffer;
    BYTE[18] headerBuffer;
    size_t oversizedDuration;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const ZSTD_seqSymbol * LLTptr;
    const ZSTD_seqSymbol * MLTptr;
    const ZSTD_seqSymbol * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyDTables_t entropy;
    U32[640] workspace;
    const void * previousDstEnd;
    const void * prefixStart;
    const void * virtualStart;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameHeader fParams;
    U64 processedCSize;
    U64 decodedSize;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    ZSTD_format_e format;
    ZSTD_forceIgnoreChecksum_e forceIgnoreChecksum;
    U32 validateChecksum;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    size_t staticSize;
    int bmi2;
    ZSTD_DDict * ddictLocal;
    const ZSTD_DDict * ddict;
    U32 dictID;
    int ddictIsCold;
    ZSTD_dictUses_e dictUses;
    ZSTD_DDictHashSet * ddictSet;
    ZSTD_refMultipleDDicts_e refMultipleDDicts;
    ZSTD_dStreamStage streamStage;
    char * inBuff;
    size_t inBuffSize;
    size_t inPos;
    size_t maxWindowSize;
    char * outBuff;
    size_t outBuffSize;
    size_t outStart;
    size_t outEnd;
    size_t lhSize;
    U32 hostageByte;
    int noForwardProgress;
    ZSTD_bufferMode_e outBufferMode;
    ZSTD_outBuffer expectedOutBuffer;
    BYTE * litBuffer;
    const BYTE * litBufferEnd;
    ZSTD_litLocation_e litBufferLocation;
    BYTE[65568] litExtraBuffer;
    BYTE[18] headerBuffer;
    size_t oversizedDuration;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const ZSTD_seqSymbol * LLTptr;
    const ZSTD_seqSymbol * MLTptr;
    const ZSTD_seqSymbol * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyDTables_t entropy;
    U32[640] workspace;
    const void * previousDstEnd;
    const void * prefixStart;
    const void * virtualStart;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameHeader fParams;
    U64 processedCSize;
    U64 decodedSize;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    ZSTD_format_e format;
    ZSTD_forceIgnoreChecksum_e forceIgnoreChecksum;
    U32 validateChecksum;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    size_t staticSize;
    int bmi2;
    ZSTD_DDict * ddictLocal;
    const ZSTD_DDict * ddict;
    U32 dictID;
    int ddictIsCold;
    ZSTD_dictUses_e dictUses;
    ZSTD_DDictHashSet * ddictSet;
    ZSTD_refMultipleDDicts_e refMultipleDDicts;
    ZSTD_dStreamStage streamStage;
    char * inBuff;
    size_t inBuffSize;
    size_t inPos;
    size_t maxWindowSize;
    char * outBuff;
    size_t outBuffSize;
    size_t outStart;
    size_t outEnd;
    size_t lhSize;
    U32 hostageByte;
    int noForwardProgress;
    ZSTD_bufferMode_e outBufferMode;
    ZSTD_outBuffer expectedOutBuffer;
    BYTE * litBuffer;
    const BYTE * litBufferEnd;
    ZSTD_litLocation_e litBufferLocation;
    BYTE[65568] litExtraBuffer;
    BYTE[18] headerBuffer;
    size_t oversizedDuration;
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
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
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
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct ZSTD_DCtx_s {
    const FSE_DTable * LLTptr;
    const FSE_DTable * MLTptr;
    const FSE_DTable * OFTptr;
    const HUF_DTable * HUFptr;
    ZSTD_entropyTables_t entropy;
    const void * previousDstEnd;
    const void * base;
    const void * vBase;
    const void * dictEnd;
    size_t expected;
    ZSTD_frameParams fParams;
    blockType_e bType;
    ZSTD_dStage stage;
    U32 litEntropy;
    U32 fseEntropy;
    struct xxh64_state xxhState;
    size_t headerSize;
    U32 dictID;
    const BYTE * litPtr;
    ZSTD_customMem customMem;
    size_t litSize;
    size_t rleSize;
    BYTE[131080] litBuffer;
    BYTE[18] headerBuffer;
}
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>U32[640] workspace</code>
</li>
<li>
<b>Field added. </b>
<code>const void * prefixStart</code>
</li>
<li>
<b>Field added. </b>
<code>const void * virtualStart</code>
</li>
<li>
<b>Field added. </b>
<code>U64 processedCSize</code>
</li>
<li>
<b>Field added. </b>
<code>U64 decodedSize</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_format_e format</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_forceIgnoreChecksum_e forceIgnoreChecksum</code>
</li>
<li>
<b>Field added. </b>
<code>U32 validateChecksum</code>
</li>
<li>
<b>Field added. </b>
<code>size_t staticSize</code>
</li>
<li>
<b>Field added. </b>
<code>int bmi2</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_DDict * ddictLocal</code>
</li>
<li>
<b>Field added. </b>
<code>const ZSTD_DDict * ddict</code>
</li>
<li>
<b>Field added. </b>
<code>int ddictIsCold</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_dictUses_e dictUses</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_DDictHashSet * ddictSet</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_refMultipleDDicts_e refMultipleDDicts</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_dStreamStage streamStage</code>
</li>
<li>
<b>Field added. </b>
<code>char * inBuff</code>
</li>
<li>
<b>Field added. </b>
<code>size_t inBuffSize</code>
</li>
<li>
<b>Field added. </b>
<code>size_t inPos</code>
</li>
<li>
<b>Field added. </b>
<code>size_t maxWindowSize</code>
</li>
<li>
<b>Field added. </b>
<code>char * outBuff</code>
</li>
<li>
<b>Field added. </b>
<code>size_t outBuffSize</code>
</li>
<li>
<b>Field added. </b>
<code>size_t outStart</code>
</li>
<li>
<b>Field added. </b>
<code>size_t outEnd</code>
</li>
<li>
<b>Field added. </b>
<code>size_t lhSize</code>
</li>
<li>
<b>Field added. </b>
<code>void * legacyContext</code>
</li>
<li>
<b>Field added. </b>
<code>U32 previousLegacyVersion</code>
</li>
<li>
<b>Field added. </b>
<code>U32 legacyVersion</code>
</li>
<li>
<b>Field added. </b>
<code>U32 hostageByte</code>
</li>
<li>
<b>Field added. </b>
<code>int noForwardProgress</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_bufferMode_e outBufferMode</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_outBuffer expectedOutBuffer</code>
</li>
<li>
<b>Field added. </b>
<code>size_t oversizedDuration</code>
</li>
<li>
<b>Field removed. </b>
<code>const void * base</code>
</li>
<li>
<b>Field removed. </b>
<code>const void * vBase</code>
</li>
<li>
<b>Field type changed. </b>
<code>const FSE_DTable * LLTptr</code> ➡️ <code>const ZSTD_seqSymbol * LLTptr</code>
</li>
<li>
<b>Field type changed. </b>
<code>const FSE_DTable * MLTptr</code> ➡️ <code>const ZSTD_seqSymbol * MLTptr</code>
</li>
<li>
<b>Field type changed. </b>
<code>const FSE_DTable * OFTptr</code> ➡️ <code>const ZSTD_seqSymbol * OFTptr</code>
</li>
<li>
<b>Field type changed. </b>
<code>ZSTD_entropyTables_t entropy</code> ➡️ <code>ZSTD_entropyDTables_t entropy</code>
</li>
<li>
<b>Field type changed. </b>
<code>ZSTD_frameParams fParams</code> ➡️ <code>ZSTD_frameHeader fParams</code>
</li>
<li>
<b>Field type changed. </b>
<code>BYTE[131080] litBuffer</code> ➡️ <code>BYTE[131104] litBuffer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const BYTE * litBufferEnd</code>
</li>
<li>
<b>Field added. </b>
<code>ZSTD_litLocation_e litBufferLocation</code>
</li>
<li>
<b>Field added. </b>
<code>BYTE[65568] litExtraBuffer</code>
</li>
<li>
<b>Field removed. </b>
<code>void * legacyContext</code>
</li>
<li>
<b>Field removed. </b>
<code>U32 previousLegacyVersion</code>
</li>
<li>
<b>Field removed. </b>
<code>U32 legacyVersion</code>
</li>
<li>
<b>Field type changed. </b>
<code>BYTE[131104] litBuffer</code> ➡️ <code>BYTE * litBuffer</code>
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
