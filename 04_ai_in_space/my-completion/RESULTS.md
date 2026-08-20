# AI in Space lab results

Lab: IBM SkillsBuild hands-on-labs / `04_ai_in_space`  
Completed: 2026-08-20  
Workspace: `C:\Users\edwar\Desktop\ai-workspace\sandbox\space-weather-predictor`

## Deliverables

- `bob_generated_code.ipynb` — Tasks 1–9 (install → dashboard)
- `models/launch_decision_model.pkl`
- `models/space_weather_data.pkl`
- `models/go_nogo_dashboard.png` — go/no-go dashboard for 2025-05-01 to 2025-07-09

## What I built

- Cleaned NASA/DONKI-derived space weather events (`space_weather_unified.csv`, 1743 rows)
- Engineered 48h risk features and scored launch risk levels
- Trained a RandomForest GO/NO-GO classifier (test accuracy ~97% on the lab split)
- Built a date-range matplotlib go/no-go dashboard

## Sample dashboard window (Task 9)

- Window: 2025-05-01 → 2025-07-09
- Overall recommendation: GO
- Days analysed: 30
- Avg risk score: 24.59 / 100
- Highest risk date: 2025-05-26 (score 80.0)

## Reflections

- IBM Bob was used to drive the lab workflow (environment, Jupyter, and notebook generation prompts).
- Fallback cells from `ai-in-space.ipynb` plus the completed Task 9 dashboard are consolidated in `bob_generated_code.ipynb` for a single runnable artifact.

## Notes

Lab results do not count toward the FlightSentry challenge project score. This folder documents completion of the August GitHub hands-on lab.
