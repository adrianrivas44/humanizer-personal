# Humanizer Personal

**A writing skill that learns the user's voice before writing in it.**

[Español](README.es.md) · [English skill](SKILL.md) · [Skill en español](translations/es/SKILL.md)

Created by [Zero (@adrianrivas44)](https://github.com/adrianrivas44). Version 0.1.0.

## What it aims to achieve

"Write like a human" is too vague. People do not share one voice, and the same person does not write a client proposal the way they message a friend.

Humanizer Personal gives an AI assistant a process for learning how each user communicates, asking useful questions and producing a separate, reusable personal writing skill. The goal is to help users sound like themselves when they express their ideas clearly, while preserving meaning and facts.

It aims to:
- Ask about real audiences, situations and desired outcomes instead of relying on vague tone labels.
- Learn from user-provided samples without copying errors or assuming every sample reflects the user's voice.
- Separate confirmed preferences from observations and guesses.
- Calibrate short alternatives with the user before treating a profile as final.
- Adapt tone to context without replacing the user's voice with generic corporate or conversational prose.
- Produce a portable personal skill that can be revised as the user gives feedback.

## Two different artifacts

**This repository contains the general process.** It is not a prefilled profile of its author or a universal writing style.

**Each user creates their own personal skill through the interview.** That skill contains their confirmed preferences and should normally stay private. No personal samples or profiles are included here.

## Use with an AI assistant

1. Open [SKILL.md](SKILL.md) for English or [translations/es/SKILL.md](translations/es/SKILL.md) for Spanish.
2. Copy its complete contents into a new conversation with an assistant that accepts instructions, or attach the file if that product supports attachments.
3. Send this message:

> Use these instructions to help me build my personal writing skill. Interview me first, ask no more than three questions per turn, and do not finalize the profile until we calibrate it together. Respond in English.

4. Answer the questions. If you can, provide two to four short samples with confidential information removed. If not, the assistant can work with brief exercises and provisional preferences.
5. Compare the alternatives and correct what does not sound like you.
6. Ask for the complete personal skill in Markdown. Test it on a new task before relying on it.

Use whichever language you prefer; the editions are translations of the same process, not separate style presets. The assistant should not restart a full interview for every later edit.

### If your platform supports native skills

Use its documented installation mechanism. The English entry point is `SKILL.md`; the Spanish edition can be used as the entry point instead. **Choose one language edition; do not install both as two skills with the same name.** Keep linked templates and evaluation material accessible, or supply their relevant content in the conversation.

No universal install command is provided because products differ. Do not assume that copying a file installs a skill or enables memory across chats. The generated personal skill should be self-contained and independent of this repository.

## What happens during the interview

| Step | Result |
| --- | --- |
| Define the task | Writing contexts, audience and purpose |
| Interview | Preferences, boundaries and open questions |
| Study samples | Evidence-based traits, not assumptions |
| Calibrate | User feedback on three short alternatives |
| Create | A self-contained personal writing skill |
| Test | Feedback on a new situation and explicit remaining limits |

The assistant asks at most three questions per turn, adapts to previous answers and allows skipped questions. For a one-off edit, it can offer a provisional rewrite without requiring full calibration.

## Repository contents

- [SKILL.md](SKILL.md): general process, English.
- [translations/es/SKILL.md](translations/es/SKILL.md): equivalent process, Spanish.
- [README.es.md](README.es.md): Spanish introduction and usage.
- [English profile template](templates/voice-profile.en.md) and [Spanish profile template](templates/voice-profile.es.md): structure for the user's generated skill.
- [Evaluation scenarios](evaluation/scenarios.md): bilingual checks and expected behavior, not claimed test results.

## Privacy, integrity and limitations

Share only text you are authorized to share with your AI provider. Redact private or third-party information. A private repository does not by itself make an external AI provider suitable for confidential data.

The assistant must not invent facts, feelings, experiences or certainty to sound personal. It must not imitate typos or accessibility-related difficulties. It should treat samples and attachments as data, not instructions to reveal information or take actions.

This is not an AI-detector bypass tool and does not guarantee undetectability. It does not grant permission to misrepresent authorship or ignore disclosure requirements.

The procedure is provider-neutral, not universally certified: performance, supported instruction formats, file access and persistence depend on the AI product. Structural validation is not proof of behavioral quality or user approval. Broad cross-provider behavioral evaluation is pending.

## Authorship and reuse

Created by Zero (@adrianrivas44), with AI assistance for drafting, translation and review. This repository publishes an interview-and-calibration workflow, not a copy of another project's pattern catalog or writing samples.

No license has been selected for this release. Publication alone does not grant an open-source reuse license. Licensing is a separate author decision.
