# Cowork Immersion · Microsoft 365 Copilot

A static, password-gated GitHub Pages site for a guided customer immersion
focused on **Microsoft 365 Copilot Cowork** (Frontier) for licensed users.

🔗 **Live site:** https://steffiyappy.github.io/contoso-cowork-immersion/
🔐 **Access code:** `ContosoCowork14May`

## What's inside

A single-page HTML app (`index.html`) with:

- **Welcome** — Overview, What is Cowork, Today's story, Get started
- **The Demo** — One realistic Cowork prompt that produces six artefacts in parallel
- **Use Cases by Division**
  - Plantation operations
  - Manufacturing / Oleochemicals
  - Property (Contoso Land)
  - Group functions (Finance, HR, Sustainability, IR, Procurement, Legal, IT)
- **Reference**
  - The 13 built-in Cowork skills mapped to Group examples
  - Prompting tips and a take-home prompt library

Demo files in `files/`:

- `01_Contoso_YieldData.xlsx` — Q1 plantation yield data
- `02_Contoso_OpsReport.docx` — Q1 Group Operations Report

## Persona & scenario

The site uses a fictional persona — **Siew Ling, Group COO at Contoso
Plantation Berhad** — preparing for her quarterly Board Operations Review.
The Group spans plantation, downstream manufacturing and Contoso Land
(property). All names, estates, numbers and people are fictional.

## Format

The session is a guided demonstration — show-and-tell, not follow-along.
Audience members are expected to be M365 Copilot licensed users.

## Reusing this site

The outer site branding is intentionally generic ("Cowork Immersion") so
this template can be reused for other customer sessions. To adapt it for a
new customer:

1. Update the password in `index.html` (search for `const PW =`)
2. Find-replace `Contoso Plantation Berhad` and `Contoso Land` if you want
   a different worked example
3. Adjust the use-case industry slant (plantation/manufacturing/property)
   to fit the customer's context
4. Optionally `gh repo rename <new-name>` and push — GitHub Pages picks up
   the new URL automatically
