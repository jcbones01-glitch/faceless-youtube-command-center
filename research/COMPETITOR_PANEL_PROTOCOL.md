# WP-001 — Competitor Comparison Panel Protocol

**Status:** OPEN  
**Purpose:** Improve the evidence base for VID-001 packaging and storytelling without copying competitors or pretending public metrics reveal private analytics.

## Research question

Among recent long-form explainers in adjacent technology/infrastructure niches, what observable differences appear between stronger and lower-relative-performing videos after accounting for channel context and video age as well as practical public data allow?

This is descriptive research, not causal inference.

## Preselected starting channels

From the launch blueprint:
- fern
- Branch Education
- Asianometry
- Wendover Productions

Add smaller relevant channels **before** ranking videos to reduce survivor bias.

## Sampling

For each channel, target 20–30 recent long-form uploads where practical.

Keep separate:
- long-form uploads
- Shorts
- livestreams

Do not mix them into one performance distribution.

## Required fields

For every sampled video record:

```yaml
channel:
video_title:
video_url:
published_at:
snapshot_at:
views_at_snapshot:
duration_seconds:
format: long_form | short | live
topic:
title_structure:
thumbnail_observations:
opening_observations:
visual_explanation_observations:
story_structure_observations:
source_signaling_observations:
watched_or_transcribed_scope:
notes:
missing_fields:
```

## Performance comparison rules

A current cumulative view count cannot reconstruct day-7 views.

Therefore:

1. Preserve publication time and observation time.
2. Begin repeat snapshots.
3. Prefer within-channel relative comparisons where possible.
4. Compare age-matched observations only when genuinely available.
5. A “lower relative performer” means lower observed performance within the defined comparison—not an unsuccessful channel or bad video.
6. Do not infer competitor CTR, retention, revenue, subscriber conversion, or satisfaction from views alone.
7. Do not infer that one visible creative difference caused the view difference.

## Qualitative coding

Code observable features consistently, including:
- specificity of title question
- curiosity gap
- concrete mechanism promised
- thumbnail text length
- thumbnail concept count
- presence of people/faces
- visual complexity
- opening question/contradiction
- time to first explanation/payoff
- use of diagrams
- narrative device
- amount of context before mechanism
- explicit source attribution
- sequel/series framing

Add fields only prospectively and document the change.

## Deliverable

Create:
- `research/competitor_panel_snapshot_YYYY-MM-DD.csv` or JSON
- `research/competitor_panel_findings_v1.md`

The findings memo must separate:
- directly observed facts
- descriptive patterns
- hypotheses worth testing
- data unavailable
- conclusions that cannot be supported

## Decision use

Use the panel only to review:
- VID-001 title candidates
- thumbnail candidates
- first 30–60 seconds
- visual explanation density
- story structure

Do not copy a competitor's wording, script structure, graphics, branding, or thumbnail composition.
