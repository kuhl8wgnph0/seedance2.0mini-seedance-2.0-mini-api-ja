# Seedance 2.0 Mini API 日本語ガイド（seedance-2.0-mini / seedance2.0mini）

> 従量課金、最低 1 ドルから、OpenAI 互換エンドポイント。 **480P-input $0.0064; 480P $0.0106; 720P-input $0.0138**

**[模型页](https://go.apimart.ai/k-89c56f) · [实时价格](https://go.apimart.ai/k-58e553) · [获取 API Key](https://go.apimart.ai/k-1aae1b)**

## 料金（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `480P-input` | $0.0064 |
| `480P` | $0.0106 |
| `720P-input` | $0.0138 |
| `720P` | $0.0229 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/videos/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"seedance-2.0-mini","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本リポジトリはサードパーティ中継サービス APIMart の利用ガイドです。
