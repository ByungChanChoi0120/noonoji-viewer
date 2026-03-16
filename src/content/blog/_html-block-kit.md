---
title: HTML Block Kit (재사용)
date: '2026-03-16'
summary: 블로그 본문에서 재사용할 UI 블록 모음
draft: true
---

## 1) TIP 박스
```html
<div style="border:1px solid #d1d5db;border-radius:12px;padding:12px;background:#f3f4f6;margin:12px 0;">
  <b>TIP</b><br/>
  핵심 메시지 한 줄
</div>
```

## 2) macOS 카드
```html
<div style="margin:16px 0;border:1px solid #cbd5e1;border-radius:14px;overflow:hidden;">
  <div style="background:#111827;color:#fff;padding:8px 12px;font-size:13px;">● ● ● macOS-style note</div>
  <div style="padding:12px 14px;background:#f8fafc;font-size:14px;line-height:1.6;">
    본문
  </div>
</div>
```

## 3) 문제-원인-조치-결과 카드
```html
<div style="display:grid;gap:10px;margin:14px 0;">
  <div style="padding:12px;border:1px solid #e5e7eb;border-radius:10px;background:#fff;"><b>문제</b><br/>...</div>
  <div style="padding:12px;border:1px solid #e5e7eb;border-radius:10px;background:#fff;"><b>원인</b><br/>...</div>
  <div style="padding:12px;border:1px solid #e5e7eb;border-radius:10px;background:#fff;"><b>조치</b><br/>...</div>
  <div style="padding:12px;border:1px solid #bbf7d0;border-radius:10px;background:#f0fdf4;"><b>결과</b><br/>...</div>
</div>
```
