# 第4回 解答

## 演習

- 基準別の一致率（直す前）：根拠　/　、範囲　/　、ヒント　/　、分かりやすさ　/　、回の表示　/　
- 要確認の件数（直す前）：
- 直した基準と、書き足した方針：
- 基準別の一致率と要確認の件数（直した後）：
- 講師のラベルと自分のラベルで判定が違った項目と、そう判定した理由：
- 気づき・疑問：

## 宿題

- 取り組んだレベル：基礎
- やったこと：
  採点のモデル（`AIE_MODEL`）だけを `gemini-3.5-flash-lite`（既定）から `gemini-3.5-flash` に変え、同じ `lectures/04/labels.jsonl` と `data/eval/rubric.md` で再実行した。
  `AIE_MODEL=gemini-3.5-flash uv run python -m app.judge --out lectures/04/judge_result_flash.json`
- 結果：
  - 変える前（gemini-3.5-flash-lite）：根拠　/　、範囲　/　、ヒント　/　、分かりやすさ　/　、回の表示　/　。総合　/　、要確認　件
  - 変えた後（gemini-3.5-flash）：根拠　/　、範囲　/　、ヒント　/　、分かりやすさ　/　、回の表示　/　。総合　/　、要確認　件
  - 判定が変わった項目：
- 気づき・疑問：
