# Day 2: TTS Testing

**Date:** [Aaj ki tareekh]
**Time:** 2 hours
**What:** Tested Azure Speech Text-to-Speech on 5 Urdu sentences

## Results
| # | Sentence | Voice | Quality |
|---|----------|-------|---------|
| 1 | Assalam o alaikum... | Uzma Neural | ✅ Natural |
| 2 | Dr. Kamran Sheikh... | Uzma Neural | ✅ Clear |
| 3 | Appointment book... | Uzma Neural | ✅ Good |
| 4 | Phone number... | Uzma Neural | ⚠️ Numbers okay |
| 5 | Shukriya... | Uzma Neural | ✅ Warm |

## Findings
- **Voice Quality:** Uzma Neural bohot natural sounds
- **Urdu Support:** Bilkul sahi — Pakistan accent present
- **Numbers:** Thik hai (phone number readable)
- **Speed:** Good for clinic use

## Next
- Download files
- Week 2 E2E pipeline (STT→LLM→TTS)

## Files Generated
- tts_azure_1.wav through tts_azure_5.wav
