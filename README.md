# HostsToEnglish

---

## English

### Hosts to Adblock filter Converter

Converts hosts-formatted text into DNS blocklists compatible with AdblockPlus syntax, for use with ad blockers such as uBlock Origin.

#### Example

**Input (hosts format):**
```
127.0.0.1 ads.example.com
0.0.0.0 tracking.site.net
```

**Output (Adblock filter format):**
```
||ads.example.com^
||tracking.site.net^
```

---

## 日本語

### Hosts to Adblock filter

Hosts形式のテキストを、uBlock Origin等の広告ブロッカーで使用可能なAdblockPlus形式のDNSブロックリストに変換します。

#### 使用例

**入力（hosts形式）：**
```
127.0.0.1 ads.example.com
0.0.0.0 tracking.site.net
```

**出力（Adblockフィルター形式）：**
```
||ads.example.com^
||tracking.site.net^
```
