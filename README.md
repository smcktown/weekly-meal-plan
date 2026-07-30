# Weekly Meal Plan

Mobile-first meal plan — **this week and next on one page**, with a week switcher at the top.
Cooking, breakfasts, snack boxes and a tickable shopping list.

**Live:** https://smcktown.github.io/weekly-meal-plan/

## Why two weeks

Shopping happens on Saturday *for the week ahead*. A single-week page always showed the
week you'd already bought for. The switcher defaults to **next week** — the one you're
actually shopping for.

## Updating

1. Edit `index.html`: the finishing week moves into the left slot (trimmed to what's left),
   the new week goes in the right slot and becomes `class="active"`.
2. **Bump the `KEY` constant** in the script so the new shopping list starts unticked.
3. Copy the file to `archive/<YYYY-wNN>/` before overwriting, so old weeks stay reachable.

## Archive

- [`archive/2026-w10/`](./archive/2026-w10/) · 27 Jul – 2 Aug
- [`archive/2026-w11/`](./archive/2026-w11/) · 3 – 9 Aug

---

Public and de-identified — roles not names, no schools, activities, places or health notes.
