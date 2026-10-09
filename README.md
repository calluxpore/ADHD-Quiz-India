<div align="center">

# 🧠 ADHD Self-Check

**A calm, private, 5-minute adult ADHD screening based on real clinical research.**

One question at a time, inspired by Typeform, over a background of geometric shapes you can play with.

[![Live Demo](https://img.shields.io/badge/▶_Try_it-live-3b5bdb?style=for-the-badge)](https://YOUR-USERNAME.github.io/YOUR-REPO/)
&nbsp;
![Single file](https://img.shields.io/badge/single_file-HTML-e34f26?style=for-the-badge&logo=html5&logoColor=white)
&nbsp;
![p5.js](https://img.shields.io/badge/p5.js-1.9.4-ed225d?style=for-the-badge&logo=p5dotjs&logoColor=white)
&nbsp;
![Private](https://img.shields.io/badge/data-stays_on_device-2f9e6b?style=for-the-badge)

</div>

---

> [!IMPORTANT]
> **This is a screening tool, not a diagnosis.** Only a qualified psychiatrist or clinical psychologist can diagnose ADHD after a full evaluation.
> In India, if you need to talk to someone now, call **Tele-MANAS 14416** (free, 24×7, Government of India).

## ✨ Features

| | |
|---|---|
| 🩺 **Research-based** | Uses the 18-item **WHO Adult ADHD Self-Report Scale (ASRS v1.1)** with its official scoring thresholds |
| 📋 **DSM-5 context** | Adds questions on childhood onset, how many areas of life are affected, impact on daily life, and conditions that can look like ADHD |
| 🇮🇳 **Made for India** | Everyday Indian examples, guidance on where to get assessed (NIMHANS, AIIMS, medical colleges), and the Tele-MANAS helpline |
| ⌨️ **Typeform-style UX** | One question per screen, moves on automatically after each answer, keyboard shortcuts, smooth transitions, progress bar |
| 🎨 **Interactive background** | p5.js shapes fall under gravity, collide and pile up, scatter from your cursor, and hop when you answer |
| 📊 **Clear results** | Screener score ring, bars for the two symptom groups, the ADHD type your pattern resembles, and notes based on your answers |
| 📄 **Shareable** | Copy a summary to show a doctor, or save the results as a PDF |
| 🔒 **100% private** | No server, no analytics, no cookies. Nothing leaves your device |
| 🌗 **Accessible** | Dark mode, reduced-motion support, works with screen readers, mobile-first layout |

## 🚀 Quick start

No build step. No dependencies to install.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
```

Then open `index.html` in any browser. That's it.

## 🌐 Deploy to GitHub Pages

1. Push `index.html` to the root of a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Your quiz will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO/` in about a minute.

## ⌨️ Keyboard shortcuts

| Key | Action |
|---|---|
| <kbd>A</kbd>–<kbd>E</kbd> or <kbd>1</kbd>–<kbd>5</kbd> | Choose an answer |
| <kbd>Enter</kbd> | Continue |
| <kbd>↑</kbd> / <kbd>↓</kbd> | Previous / next question |

## 🧮 How scoring works

Each ASRS answer runs from *Never* to *Very often*. An answer counts as **clinically significant** at:

- **"Sometimes" or more** for items 1, 2, 3, 9, 12, 16 and 18
- **"Often" or more** for all other items

| Result | Rule |
|---|---|
| 🔴 **Highly consistent with ADHD** | 4 or more significant answers in Part A (items 1–6), the ASRS screener cut-off |
| 🟠 **Some signs worth exploring** | 3 in Part A, **or** 5 or more significant symptoms in either symptom group |
| 🟢 **ADHD unlikely** | Neither of the above |

The symptom groups follow DSM-5:

- **Inattention:** items 1–4 and 7–11
- **Hyperactivity / impulsivity:** items 5, 6 and 12–18

Each group is compared with the DSM-5 adult threshold of **5 symptoms**.

## 🎛️ Customise

All the code lives in `index.html`.

| What | Where |
|---|---|
| Colours | CSS variables in `:root` at the top of the file. The background shapes use them too |
| Questions & hints | The `ASRS` array |
| Physics feel | `GRAVITY`, `REPEL_R` and `REPEL_F` in the background script |
| Shape opacity | The fill and outline alpha values (`30` and `90`) in `p.draw` |

## 📚 Research & sources

- Kessler RC, Adler L, Ames M, et al. *The World Health Organization Adult ADHD Self-Report Scale (ASRS): a short screening scale for use in the general population.* **Psychological Medicine**, 2005;35(2):245–256.
- World Health Organization. *Adult ADHD Self-Report Scale (ASRS v1.1) Symptom Checklist.*
- American Psychiatric Association. *DSM-5-TR*, 2022: ADHD criteria A–E.
- World Health Organization. *ICD-11*, code 6A05.
- Indian Psychiatric Society: Clinical Practice Guidelines for ADHD (*Indian Journal of Psychiatry*).
- Fayyad J, et al. *The descriptive epidemiology of DSM-IV Adult ADHD in the WHO World Mental Health Surveys.* **ADHD Atten Def Hyp Disord**, 2017;9(1):47–65.
- Ministry of Health & Family Welfare, Govt. of India: [Tele-MANAS](https://telemanas.mohfw.gov.in).

> [!NOTE]
> The ASRS v1.1 questionnaire is © World Health Organization. Please review the WHO terms of use before redistributing it.

## 🛠️ Built with

- Plain **HTML, CSS & JavaScript**: no frameworks, no build step
- [**p5.js**](https://p5js.org) for the interactive physics background
- [**Fraunces**](https://fonts.google.com/specimen/Fraunces) & [**Inter**](https://fonts.google.com/specimen/Inter) from Google Fonts

---

<div align="center">

Made with 💙 to help more people in India understand their minds and get the right support.

<sub>If this helped you, consider ⭐ starring the repo and sharing it with someone who might need it.</sub>

</div>
