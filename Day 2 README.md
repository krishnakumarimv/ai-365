# Day 2 — Why AI Matters

Part of the **AI 365** series: one beginner-friendly AI concept a day, with a hands-on exercise to go with it.

## Topic

AI isn't a distant, futuristic idea — it's already the invisible layer behind apps you use every day:

- Swiggy predicting your order before you open the app
- Hotstar picking which cricket highlights to show you first
- Face ID deciding in 0.1 seconds that it's really you

Understanding how it works is becoming as basic a life skill as reading a contract or understanding interest rates, because it quietly shapes things like loan approvals, job listings, and what news reaches you first.

## Exercise: Spot the Invisible AI

**Task:** Write a simple Python rule-based program that scans a set of everyday app notifications and flags which ones show AI quietly making a decision *for* you.

**Dataset:** `Synthetic Messages` — 10 short, made-up app notifications (defined inline in the notebook, no external file needed).

**Approach (hint):** Build a small list of "invisible AI" signal phrases — `recommended for you`, `predicted`, `detected`, `auto-selected`, `personalized` — and check whether each message contains one.

**What to submit:** Runnable notebook cell(s) + result + a 2-3 sentence interpretation of what you found.

## Files

| File | Description |
|---|---|
| `day2_try_it_yourself.ipynb` | Runnable notebook with the exercise solution, real output, and interpretation |

## Result

```
Messages flagged as AI-driven: 5 / 10
```

## Interpretation

Half of the 10 messages were flagged as AI-driven, showing how often a system is quietly recommending, predicting, or detecting something on your behalf without ever saying "AI" out loud. A simple keyword check like this is a useful first filter, but it's rule-based, not intelligent — it would miss an AI-driven message phrased differently (e.g. "picked just for you") and could wrongly flag a human-written message that happens to use one of the words.

## How to run

1. Open `day2_try_it_yourself.ipynb` in Jupyter or Google Colab.
2. Run all cells — no installs or external data files required.
3. Try adding your own messages or signal phrases to see how the results change.

## Learning outcome

By the end of this exercise, you should be able to write a basic rule-based text classifier in Python, and explain why keyword matching is a limited but useful first approach to detecting patterns in text.

---
🔗 Join the channel: [whatsapp.com/channel/0029VbCHNrh59PwTRYmQsQ0i](https://whatsapp.com/channel/0029VbCHNrh59PwTRYmQsQ0i)
