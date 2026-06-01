# Prompt Log - FUTURE_PE_02

## Objective

Generate a complete UGC ad content pack for a D2C product using structured prompt engineering.

## Prompt Engineering Decisions

- The model was assigned the role of UGC ad strategist.
- Product benefits and audience groups were included before asking for scripts.
- Hooks were generated separately because the first 3 seconds are critical for short-form ads.
- Scripts followed a clear structure: hook, problem, product, benefit, reaction, CTA.
- Platform adaptation was requested after the main scripts so each version could match channel behavior.

## Reusable Master Prompt

```text
Act as a UGC ad strategist and short-form video copywriter.

Create a UGC ad content pack for this product:
- Brand:
- Product:
- Category:
- Main benefits:
- Target audience:
- Brand voice:
- Main conversion goal:
- Platforms:

Return:
1. Audience pain points
2. 20 short hooks
3. 5 UGC ad scripts using problem-solution-CTA structure
4. Platform adaptations for Instagram Reels, Facebook Reels, and YouTube Shorts
5. Caption pack
6. CTA variations

Rules:
- Keep the tone natural and creator-like.
- Focus on conversion, not generic awareness.
- Avoid unrealistic claims.
- Make scripts easy to film with a phone.
```

## Improvement Notes

The strongest scripts came from defining the specific situation first, such as office break, study routine, hosting friends, or post-walk refreshment. This made the ad feel more authentic and less like a direct sales pitch.
