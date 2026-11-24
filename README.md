# Proof Without Paper

A free web tool that helps skilled refugees show what they can do when their certificates, diplomas and records are lost.

Built for the Power Learn Project Africa Mini Hackathon, "Unlocking Displaced Talent: Pathways for Skilled Refugees" (November 24 to 27, 2026).

## The problem

Many skilled refugees fled without their documents. Credential recognition, job applications and professional registration usually start with paperwork, so people with years of real experience can be treated as if they have none.

## What this tool does

Proof Without Paper gives someone a way to start without the paperwork.

1. **Describe your work.** Enter your profession, years of experience, last workplace and the country where you worked.
2. **Rate what you have done.** For six core tasks in your profession, say whether you have never done it, done it occasionally, done it regularly, or done it regularly and trained others.
3. **Say what you can still reach.** Tick which sources of evidence you can still contact, such as a former employer, colleagues, your school, old files or an ID document.

The tool then produces:

- **A competency portfolio:** a written summary and a table of tasks and experience levels, which can be printed or saved as a PDF.
- **A recovery plan:** steps for rebuilding evidence of your qualifications. Steps for sources you can reach come first, under "Start here".
- **A draft letter** requesting a reference from a former employer, ready to copy.

Supported professions: nurse or midwife, teacher, civil engineer and accountant.

## Hackathon tracks it supports

- **Credential recognition:** builds structured evidence of skills when documents are missing, and points users to the recognition authority and to alternative assessment routes.
- **Local professional networks:** the plan encourages finding former colleagues and professional groups who can confirm a person's work.
- **Legal and financial access:** the plan covers identity and registration documents and warns users to confirm fees and rules before paying for any assessment.

## Important limits

- The portfolio is a **self-assessment**. It becomes evidence only when backed by letters, signed statements or an assessment by a recognized authority.
- The tool gives **general guidance, not legal advice**. Recognition rules differ by country, profession and authority, so users must confirm requirements with the authority that will assess them.
- It does not guarantee that any authority or employer will recognize a person's skills.

## Privacy

Everything a user enters is processed in the browser. The site has no server component, no database, no accounts, no cookies and no analytics. Nothing is sent anywhere. The hosting provider may keep standard technical logs, as any website host does. The site includes a privacy policy page and a terms and conditions page.

## How it is built

- A single `index.html` file with plain HTML, CSS and JavaScript.
- No frameworks, no build step and no external dependencies.
- No network requests, so it works reliably during a demo.
- Light and dark color themes that follow the device setting.
- Responsive layout and a print stylesheet for the portfolio.

## Run it locally

1. Clone or download this repository.
2. Open `index.html` in any modern browser.

## Deploy with GitHub Pages

1. Push the repository to GitHub as a public repository.
2. Go to **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, and save.
4. To use your own domain, enter it in the **Custom domain** box on the same page and add the DNS records GitHub lists.

## Roadmap

- Language switch for Arabic, Somali, Swahili and French.
- More professions and task lists, reviewed with people working in those fields.
- Country-specific guidance that links to official recognition authorities, each verified against its source.
- An optional "ask a question" assistant, with a clear privacy notice about data leaving the device.

## Files

- `index.html`: the whole application, including the privacy and terms pages.
- `README.md`: this file.
