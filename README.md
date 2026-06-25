# public-feedback

This repository is a public feedback hub for released products, including books, websites, services, apps, and other projects.

You can use this repository to report errors, suggest improvements, ask questions, or share feedback about any supported product listed here.

---

このリポジトリは、書籍・Webサイト・サービス・アプリなど、公開しているプロダクトへのフィードバックを受け付けるための場所です。

誤り報告、改善提案、質問、感想などがありましたら、対象プロダクトの案内を確認したうえで GitHub Issues からお知らせください。

## If You Are Not Familiar with GitHub

If you are not familiar with GitHub or are not sure how to create an Issue, you can send your feedback directly by email.

Please contact:

**Daisuke Masuda（増田 大輔）**  
**daisuke+feedback@masuda.tokyo**

When sending feedback by email, please include the product name and the relevant section, page, URL, or other location information if possible.

## GitHub の使い方がよくわからない方へ

GitHub の使い方がよくわからない方、Issue の作成方法がわからない方は、メールで直接フィードバックを送っていただいても構いません。

連絡先:

**Daisuke Masuda**  
**daisuke+feedback@masuda.tokyo**

メールでご連絡いただく場合は、可能であれば、対象プロダクト名、該当する章・ページ・URL・画面名などを一緒に書いてください。

## Purpose

The purpose of this repository is to provide a single, organized place for feedback on public products.

Each product has its own folder. Please check the relevant folder before creating an Issue, as each product may have its own notes, scope, and reporting guidelines.

Examples of feedback include:

- Typographical errors
- Broken links
- Incorrect explanations
- Technical corrections
- Display or formatting issues
- Usability issues
- Documentation improvements
- Feature suggestions
- Questions about published content
- General feedback

## Products

Currently supported products are listed below.

| Product | Type | Folder                                                                                                                                                                                                                                                                                                                                                                                          |
|---|---|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Java 21 スペシャリスト問題集 | Book | [`書籍『Java 21 スペシャリスト問題集』〜300問で鍛える実務Javaエンジニアの知識体系〜/`](./tree/main/%E6%9B%B8%E7%B1%8D%E3%80%8EJava%2021%20%E3%82%B9%E3%83%9A%E3%82%B7%E3%83%A3%E3%83%AA%E3%82%B9%E3%83%88%E5%95%8F%E9%A1%8C%E9%9B%86%E3%80%8F%E3%80%9C300%E5%95%8F%E3%81%A7%E9%8D%9B%E3%81%88%E3%82%8B%E5%AE%9F%E5%8B%99Java%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%AE%E7%9F%A5%E8%AD%98%E4%BD%93%E7%B3%BB%E3%80%9C) |

More products may be added in the future.

## Repository Structure

This repository is organized by product.

```text
public-feedback/
├── README.md
├── 書籍『Java 21 スペシャリスト問題集』〜300問で鍛える実務Javaエンジニアの知識体系〜/
│   └── README.md
└── .github/
    └── ISSUE_TEMPLATE/
        ├── typo.yml
        ├── technical-correction.yml
        ├── improvement.yml
        └── question.yml
```

The root `README.md` explains the overall purpose of this repository.

Each product folder contains product-specific information, such as:

- Product overview
- Feedback scope
- How to report issues
- Known notes or limitations
- Product-specific labels or examples
- Links to related pages

## How to Submit Feedback

Please submit feedback by creating a GitHub Issue.

Before creating an Issue, please do the following:

1. Check whether the product is listed in this repository.
2. Open the product-specific folder.
3. Read the product-specific `README.md`.
4. Search existing Issues to avoid duplicates.
5. Create a new Issue using the most appropriate template.

If you prefer not to use GitHub, you may send feedback by email as described near the top of this README.

When reporting feedback, please include as much detail as possible.

Useful information may include:

- Product name
- Version, edition, or release date, if applicable
- Page number, section name, chapter name, or URL
- Environment, browser, OS, or device, if relevant
- Current behavior or current text
- Expected behavior or suggested correction
- Screenshots, logs, or code snippets, if useful
- Links to official documentation or references, if applicable

## Issue Types

The following types of Issues are generally welcome.

### Typo

Use this for typographical errors, incorrect wording, broken sentences, or small formatting mistakes.

Examples:

- Misspelled words
- Incorrect punctuation
- Broken Markdown formatting
- Inconsistent terminology
- Kindle or web display issues

### Technical Correction

Use this when the content may be technically incorrect or misleading.

Examples:

- Incorrect code
- Outdated technical explanation
- Wrong command or option
- Version-specific behavior
- Missing warning or limitation
- Incorrect reference to a specification or official document

### Improvement

Use this for suggestions that would make the product more useful, clear, or complete.

Examples:

- Better explanation
- Additional examples
- New topics to cover
- Improved structure
- Better wording
- More helpful documentation

### Question

Use this when you want to ask a question about a product.

Examples:

- Clarification about published content
- Question about intended behavior
- Question about examples or explanations
- Question about product scope

## Issue Title Guidelines

Please use a clear Issue title.

Good examples:

```text
[Java 21 Book] Chapter 2: Add note about Preview features
[Java 21 Book] Question 091: Clarify volatile and atomicity
[Website] Broken link on pricing page
[App] Login screen does not display correctly on mobile
[Service] API documentation example returns unexpected response
```

Less helpful examples:

```text
Bug
Question
It does not work
Typo
Please fix
```

Clear titles make it easier to confirm, discuss, and resolve feedback.

## Labels

Issues may be organized using labels such as:

- `typo`
- `technical-correction`
- `clarification`
- `question`
- `enhancement`
- `documentation`
- `bug`
- `formatting`
- `needs-info`
- `accepted`
- `fixed`
- `wontfix`

Labels may change as repository operations evolve.

## Pull Requests

Pull Requests are welcome when they help clarify or fix public-facing content.

Before submitting a Pull Request, please consider opening an Issue first, especially for larger changes.

Pull Requests may be used for:

- Typo fixes
- Documentation improvements
- Link corrections
- Example corrections
- Product-specific README updates
- Issue template improvements

Please note that all Pull Requests are reviewed before being accepted. A suggested change may be modified, partially accepted, or declined depending on the product direction, scope, and editorial policy.

## Scope

This repository is intended for feedback on public products.

In scope:

- Released books
- Public websites
- Public services
- Public apps
- Public documentation
- Public sample materials
- Public learning resources

Out of scope:

- Private project support
- Individual consulting requests
- Debugging private codebases
- Security testing of third-party systems
- Requests involving confidential information
- Customer support unrelated to listed products
- Offensive, abusive, or inappropriate content

## Security and Sensitive Information

Do not post sensitive information in public Issues or public comments.

Please avoid sharing:

- Passwords
- API keys
- Access tokens
- Private URLs
- Personal information
- Customer data
- Internal logs containing secrets
- Vulnerability details that could be directly abused

If your feedback involves a potential security issue, please provide only a high-level summary in a public Issue unless the product-specific README provides another reporting method.

If you are unsure whether the information should be public, please send an email first.

## Use of Submitted Feedback

By submitting an Issue, comment, Pull Request, or email, you understand that your feedback may be used to improve related products.

Submitted feedback may be used for:

- Corrections
- Revisions
- Documentation updates
- Future editions
- Product improvements
- Public release notes
- Supplementary materials

Your GitHub username and public comments may remain visible on GitHub.

Please do not include information that you do not want to make public.

## Copyright

The content of each product remains owned by its respective author or rights holder.

Please do not post large excerpts from books, paid content, private materials, or copyrighted works. Short excerpts necessary for reporting an issue are acceptable.

When quoting content, please include only the minimum necessary context.

## Language

Issues and emails may be written in Japanese or English.

For Japanese-language products, Japanese is preferred.  
For English-language products, English is preferred.

Either language is welcome as long as the feedback is clear.

## Response Policy

Feedback will be reviewed as time allows.

Not all Issues or emails will receive an immediate response. Some Issues may be closed after review, merged into other Issues, or addressed in a future update.

Possible outcomes include:

- Accepted and fixed
- Accepted for a future update
- Clarified in discussion
- Marked as duplicate
- Closed because it is out of scope
- Closed because there is not enough information
- Closed because no change is planned

## Before Opening an Issue or Sending Email

Please check the following:

- Is the product listed in this repository?
- Have you read the product-specific README?
- Has the same issue already been reported?
- Is your description specific enough to reproduce or understand the issue?
- Have you removed any sensitive or private information?

## Contact

For feedback about a specific product, GitHub Issues are preferred.

If you are not familiar with GitHub, you may contact:

**Daisuke Masuda**  
**daisuke+feedback@masuda.tokyo**

## Thank You

Thank you for taking the time to report issues, suggest improvements, and share feedback.

Clear and thoughtful feedback helps make each product more accurate, useful, and reliable.
